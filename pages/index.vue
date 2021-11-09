<template>
  <v-app>
    <div class="flex">
      <v-navigation-drawer permanent>
        <v-list-item>
          <v-list-item-content>
            <v-list-item-title class="text-h6">
              Routing
            </v-list-item-title>
            <v-list-item-subtitle>
              subtext
            </v-list-item-subtitle>
          </v-list-item-content>
        </v-list-item>

        <v-divider></v-divider>

        <v-list
          dense
          nav
          v-for="item in items"
          v-bind:key="item"
        >
          <v-list-item link>
            <v-list-item-content>
              <NuxtLink :to="'/' + item">
                User {{item}}
              </NuxtLink>
            </v-list-item-content>
          </v-list-item>
        </v-list>
      </v-navigation-drawer>
      <div>
        <NuxtChild/>
      </div>
    </div>
  </v-app>
</template>

<script>
export default {
  data() {
    return {
      items: [
        1, 2, 3, 4, 5, 6
      ]
    }
  }
}
</script>

<style>
.flex {
  display: flex;
}
</style>