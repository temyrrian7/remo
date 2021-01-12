<template>
  <div id="app">
    <HelloWorld msg="Welcome to Your Vue.js App" />
    <footer class="footer fixed-bottom mt-5">
      <div class="container">
        <span class="text-muted">Place sticky footer content here.</span>
      </div>
    </footer>
  </div>
</template>

<script>
import "bootstrap/dist/js/bootstrap.bundle";
import HelloWorld from "./components/HelloWorld.vue";

import Vue from 'vue'
import VueRouter from 'vue-router'

Vue.use(VueRouter)

export default {
  name: "App",
  components: {
    HelloWorld,
  },
};

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
