<template>
  <v-app>
    <v-content>
      <MainNavigation />
    </v-content>
  </v-app>
</template>

<script lang="ts">
import Vue from "vue";
import MainNavigation from "./components/MainNavigation.vue";

export default Vue.extend({
  name: "App",

  components: {
    MainNavigation
  },

  data: () => ({
    //
  })
});
</script>
