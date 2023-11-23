<template >
  <div class="container">
    <Navbar />
    <Hero />
    <Portfolio />
    <Footerr />
  </div>
</template>

<script>
import Navbar from './components/Navbar.vue';
import Hero from './components/Hero.vue'
import Portfolio from './components/Portfolio.vue'
import Footerr from './components/Footerr.vue'


export default {
    components: {
      Navbar,
      Hero,
      Portfolio,
      Footerr
      
    }
}
</script>

<style >
  .container{
    width: 100%;
    max-width: 1380px;
    margin: 0 auto;
    padding: 0 16px;
    box-sizing: border-box;
  }
</style>