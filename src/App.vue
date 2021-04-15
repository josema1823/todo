<template class="app">
  <v-app>
    <Navbar />
    <v-main>
      <router-view />
    </v-main>
  </v-app>
</template>

<script lang="ts">
import Vue from "vue";
import Navbar from "./components/Navbar.vue";
import { Component } from "vue-property-decorator";

@Component({ components: { Navbar } })
export default class App extends Vue {}
</script>

<style lang="scss">
@import "@/scss/main.scss";
html,
body {
  overflow: auto;
  * {
    box-sizing: border-box;
  }
}
</style>
