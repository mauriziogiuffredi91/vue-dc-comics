<template>
  <div id="app">
    
    <!-- Header -->
    <Header />

    <!-- Main -->

    <!-- Footer -->
  </div>
</template>

<script>
import Header from '@/components/Header.vue';


export default {
  name: 'App',
  components: {
      Header
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
    
  }
</style>
