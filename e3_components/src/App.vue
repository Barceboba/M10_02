<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/blogo.png">
    <!--<HelloWorld msg="Welcome to Your Vue.js App"/>-->
    <modalBootstrap></modalBootstrap>
  </div>
</template>

<script>
//import HelloWorld from './components/HelloWorld.vue'
import ModalBootstrap from './components/ModalBootstrap.vue'

export default {
  name: 'App',
  components: {
   // HelloWorld,
    ModalBootstrap
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
