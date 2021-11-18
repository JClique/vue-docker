<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/vue-logo.png" style="height: 150px;">
    <img alt="Docker logo" src="./assets/docker-logo.png" style="height: 150px;">
    <HelloWorld msg="Welcome to Your Vue.js & Docker App"/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    HelloWorld
  }
}
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
