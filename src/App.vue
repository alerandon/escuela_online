<template>
  <div id="app"> 
    <Navbar />
    <Areas />
    <Footer />
  </div>
</template>

<script>
import Navbar from './components/Navbar.vue'
import Areas from './components/Areas.vue'
import Footer from './components/Footer.vue'

export default {
  name: 'app',
  components: {
    Navbar, 
    Areas,
    Footer
  }
}
</script>

<style>
#app {
  font-family: 'Roboto', sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
