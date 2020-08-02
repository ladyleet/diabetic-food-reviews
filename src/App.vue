<template>
  <v-app>
    <v-content>
      <Header />
      <MainBody />
    </v-content>
  </v-app>
</template>

<script lang="ts">
import Vue from "vue";
import HelloWorld from "./components/HelloWorld.vue";
import Header from "./components/Header.vue";
import MainBody from "./components/MainBody.vue";

export default Vue.extend({
  name: "App",

  components: {
    HelloWorld,
    Header,
    MainBody
  },

  data: () => ({
    //
  })
});
</script>
