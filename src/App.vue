<template>
  <div id="app">
    
    <!-- Header -->
    <Header />

    <!-- Main -->

    <Banner/>

    <Series/>
    <!-- Footer -->

    <Hero/>

    <Footertop/>

    <Footerbottom/>
  </div>
</template>

<script>
import Header from '@/components/Header.vue';
import Banner from '@/components/Banner.vue';
import Series from '@/components/Series.vue';
import Hero from '@/components/Hero.vue';
import Footertop from '@/components/Footertop.vue';
import Footerbottom from '@/components/Footerbottom.vue';



export default {
  name: 'App',
  components: {
      Header,
      Banner,
      Series,
      Hero,
      Footertop,
      Footerbottom,
    
  }
}
</script>

<style lang="scss">
@import './styles/general.scss';
  
</style>
