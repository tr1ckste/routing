<template>
  <v-app>
    <v-container fluid>
      <v-app-bar
        color="orange"
        dense
        dark
        >
        <v-spacer/>
        <v-btn class="ml-3" to="/tutorials">Tutorials</v-btn>
        <v-btn class="ml-3" to="/">Home</v-btn>
      </v-app-bar>
    </v-container>
    <p class="ml-3">Side tutorial</p>
  </v-app>
</template>

<script lang="ts">
import Vue from 'vue'


export default Vue.extend({})
</script>

<style>

</style>