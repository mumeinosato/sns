<template>
  <div id="app">
    <Sidebar />
    <router-view />
    <Footer />
  </div>
</template>

<script>
import Sidebar from './components/Sidebar.vue'
import Footer from './components/Footer.vue'
export default {
  components: {
    Sidebar,
    Footer
  }
}
</script>

<style>
body {
  margin: 0;
}
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>