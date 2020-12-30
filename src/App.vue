<template>
  <v-app>
    <Header/>
    <v-main class="ma-0 pa-0">
      <Home />
    </v-main>
    <Footer />
  </v-app>
</template>

<script>
import Header from '@/components/Header.vue';
import Footer from '@/components/Footer.vue';
import Home from '@/views/Home.vue';

export default {
  name: 'App',

  components: {
    Header,
    Footer,
    Home,
  },

  data: () => ({
    //
  }),
};
</script>
