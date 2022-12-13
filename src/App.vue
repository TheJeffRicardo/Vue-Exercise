<template>
  <Navbar></Navbar>
  <router-view/>
  <Feet></Feet>
</template>

<script>
import Feet from './components/Footer.vue'
import Navbar from './components/Navbar.vue';
export default {
    components: { Navbar,Feet }
}
</script>


<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
