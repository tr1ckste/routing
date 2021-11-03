<template>
  <v-app>
    <v-container fluid>
      <v-app-bar
        color="orange"
        dense
        dark
        >
        <v-btn class="ml-3" to="/subjects/pe">Physical Education</v-btn>
        <v-btn class="ml-3" to="/subjects/pe/math">Math</v-btn>
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
