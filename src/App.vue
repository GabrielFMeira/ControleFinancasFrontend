<template>
  <Navbar/>
  <router-view/>
  <Footer/>
</template>

<script>
  import Navbar from './components/Navbar.vue';
  import Footer from './components/Footer.vue';

  export default {
    components: {
      Navbar,
      Footer
    }
  }
</script>

<style>

  body {
    margin: 0;
    background-color: #87d8b2;
  }

  .main-container{
    min-height: 100vh;
    height:fit-content;
  }

</style>
