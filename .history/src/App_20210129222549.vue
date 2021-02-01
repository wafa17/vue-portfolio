<template>
  <div id="app">
  <navigation/>
  <router-view></router-view>
  </div>
</template>

<script>
import Navigation from "./components/includes/Navigation.vue"
// import router from "./router' //import router.js into main.js"
// import Vue from "vue"

export default {
  name: "App",
  components: {
    Navigation
  }
}
</script>

<style>
#app {
  font-family: 'Poppins', 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans';
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
