<template>
  <div id="app">
    
    <!-- Header -->
    <Header />

    <!-- Main -->

    <Banner/>
    <!-- Footer -->
  </div>
</template>

<script>
import Header from '@/components/Header.vue';
import Banner from '@/components/Banner.vue';


export default {
  name: 'App',
  components: {
      Header,
      Banner,
  }
}
</script>

<style>

  /* Regole generali*/
  *{
    box-sizing: border-box;
    padding: 0;
    margin: 0;
  }

  body{
    font-family: 'Roboto Slab', serif;
  }
</style>
