<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
    <BaseTitle/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import BaseTitle from './components/BaseTitle.vue'

export default {
  name: 'App',
  components: {
    HelloWorld,
    BaseTitle
  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
