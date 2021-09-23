<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="A boinazos entre padre e hijo"/>
   <!-- <Fill msg="Al llarg del cami plegats"/> -->
    <Pare msg="La vostra covardia és esfereïdoraa"/>  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import Pare from './components/Pare.vue'
//import Fill from './components/Fill.vue'

export default {
  name: 'App',
  components: {
    HelloWorld,
    Pare

  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #4b214d;
  margin-top: 60px;
}
</style>
