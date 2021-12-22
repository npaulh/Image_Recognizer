<template>
  <v-app>
    <Header />
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
import Header from './components/Header.vue';

export default {
  name: 'App',
  components: {
    Header,
  },
  mounted() {
    const recaptchaScript = document.createElement('script');
    recaptchaScript.setAttribute('src', 'https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js');
    document.head.appendChild(recaptchaScript);
  },
};
</script>
