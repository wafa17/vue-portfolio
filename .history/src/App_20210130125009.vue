<template>
  <div>
  <navigation/>
  <div id="app">
  <router-view></router-view>
  <Footer/>
  </div>
  </div>
</template>

<script>
import Navigation from "./components/includes/Navigation.vue"
import Footer from "./components/includes/Footer.vue"
// import router from "./router' //import router.js into main.js"
// import Vue from "vue"

export default {
  name: "App",
  components: {
    Navigation,
    Footer
  }
}
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@700&display=swap');
#app {
  font-family: 'Poppins',sans-serif;
  text-align: center;
  color: #2c3e50;
  margin-top: 0px;
}
</style>
