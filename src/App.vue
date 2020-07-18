<template>
  <v-app>
    <v-content>
      <HelloWorld />
      <SideBar />
    </v-content>
  </v-app>
</template>

<script lang="ts">
import Vue from "vue";
import HelloWorld from "./components/HelloWorld.vue";
import SideBar from "./components/SideBar.vue";

export default Vue.extend({
  name: "App",

  components: {
    HelloWorld,
    SideBar,
  },

  data: () => ({
    //
  }),
});
</script>
