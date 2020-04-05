<template>
  <v-app>
    <v-app-bar
      app
      color="black"
      dark
      height="82px"
    >
      <div class="d-flex align-center">
        <v-img
          alt="Vuetify Logo"
          class="shrink mr-2"
          contain
          src="./imgs/tasti-icon-light.png"
          transition="scale-transition"
          width="80"
        />
      </div>

      <v-spacer></v-spacer>

      <div class="text-center">
        <v-btn rounded class="hover_color font-weight-black hover_text" large outlined dark width="180px">Apply Now</v-btn>
      </div>
    </v-app-bar>

    <v-content>
      <HelloWorld/>
    </v-content>
  </v-app>
</template>
<style scoped>
.hover_color:hover{
  background: #66b873;
}
.hover_text{
  color:rgb(112, 207, 112);
}
.hover_text:hover{
  color: white;
}
</style>
<script>
import HelloWorld from './components/HelloWorld';

export default {
  name: 'App',

  components: {
    HelloWorld,
  },

  data: () => ({
    //
  }),
};
</script>
