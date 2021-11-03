<template>
  <v-app>
    <v-container fluid>
      <v-app-bar
        color="orange"
        dense
        dark
        >
        <v-btn class="ml-3" to="/tutorials/main">Main</v-btn>
        <v-btn class="ml-3" to="/tutorials/main/side">Side</v-btn>
        <v-spacer/>
        <v-btn class="ml-3" to="/">Home</v-btn>
      </v-app-bar>
    </v-container>
  </v-app>
</template>

<script lang="ts">
import Vue from 'vue'


export default Vue.extend({})
</script>

<style>

</style>