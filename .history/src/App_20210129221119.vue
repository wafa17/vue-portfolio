<template>
  <div id="app">
  <navigation/>
  </div>
</template>

<script>
import Navigation from "./components/includes/Navigation.vue"
import router from "./router' //import router.js into main.js"
import Vue from "vue"

export default {
  name: "App",
  components: {
    Navigation
  }
}
new Vue({
  render: h => h(App),
  store,
  router //added router instance
}).$mount('#app')

</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
