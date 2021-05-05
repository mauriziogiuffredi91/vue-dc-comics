<template>
  <div id="app">
    
    <!-- Header -->
    <Header />

    <!-- Main -->

    <Banner/>

    <Series/>
    <!-- Footer -->
  </div>
</template>

<script>
import Header from '@/components/Header.vue';
import Banner from '@/components/Banner.vue';
import Series from '@/components/Series.vue';
import Hero from '@/components/Hero.vue';


export default {
  name: 'App',
  components: {
      Header,
      Banner,
      Series,
      Hero,
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

  .main-box{
    max-width: 1255px;
    margin: 0 auto;
  }
</style>
