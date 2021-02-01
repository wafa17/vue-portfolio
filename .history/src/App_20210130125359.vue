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

#app {
  font-family: 'Poppins';
  text-align: center;
  color: #2c3e50;
  margin-top: 0px;
}
</style>
