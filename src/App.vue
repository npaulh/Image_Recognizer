<template>
  <v-app>
    <AppHeader />
    <v-main>
    <v-container fluid>
      <router-view></router-view>
    </v-container>
    </v-main>
    <v-footer app>
      <!-- -->
    </v-footer>
  </v-app>
</template>

<script>
import AppHeader from './components/Header.vue'

export default {
  name: 'App',
  components: {
    AppHeader
  }
}
</script>
