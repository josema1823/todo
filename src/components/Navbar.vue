<template>
  <div class="navbar">
    <v-app-bar app color="accent">
      <div class="d-flex align-center">
        <v-img
          alt="Todo Name"
          class="shrink mt-1 hidden-sm-and-down"
          contain
          min-width="200"
          src="../../src/assets/todo.png"
          width="100"
        />
      </div>
      <v-spacer></v-spacer>
      <div>
        <span class="mr-2" style="color: white">¿Algo Por Hacer?</span>
        <v-icon color="white">mdi-message-bulleted</v-icon>
      </div>
    </v-app-bar>
  </div>
</template>

<script lang="ts">
import Vue from "vue";
import { Component } from "vue-property-decorator";

@Component({})
export default class Navbar extends Vue {}
</script>

<style lang="scss" scoped></style>
