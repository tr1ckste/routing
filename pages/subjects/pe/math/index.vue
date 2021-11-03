<template>
  <v-app>
    <v-container fluid>
      <v-app-bar
        color="orange"
        dense
        dark
        >
        <v-btn class="ml-3" to="/subjects/pe/math/algebra">Algebra</v-btn>
        <v-btn class="ml-3" to="/subjects/pe/math/geometry">Geometry</v-btn>
        <v-spacer/>
        <v-btn class="ml-3" to="/subjects">Subjects</v-btn>
      </v-app-bar>
    </v-container>
    <p class="ml-3">Math</p>
  </v-app>
</template>

<script lang="ts">
import Vue from 'vue'


export default Vue.extend({})
</script>

<style>

</style>