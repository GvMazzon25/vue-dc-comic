
<template>
  <div id="app">
    <!--Header-->
    <Header />
    <!--Main-->
    <main>
      <Main />
    </main>
  <!--footer-->
  <footer>
    <Footer />
  </footer>

  </div>
</template>

<script>
import Header from '@/components/Header.vue';


export default {
  name: 'App',
  components: {
    Header,
  },

};
</script>

<style lang='scss'>
 @import '@/components/generals.scss';
</style>