<template>
  <div id="app">
    <!-- HEADER -->
  <Header />

  <!-- MAIN -->
  <Main />

  <!-- FOOTER -->
  <Footer />
  </div>

</template>

<script>
import Header from '@/components/Header.vue';
import Main from '@/components/Main.vue';
import Footer from '@/components/Footer.vue';

export default {
  name: 'app',
  components: {
    Header,
    Main,
    Footer
  },
}
</script>

<style lang="scss">

</style>
