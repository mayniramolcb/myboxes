<template>
  <div id="app">
    <HelloBoxes msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>
import HelloBoxes from './components/HelloBoxes.vue'

export default {
  name: 'App',
  components: {
    HelloBoxes
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
