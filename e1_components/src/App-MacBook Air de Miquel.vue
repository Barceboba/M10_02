<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <padre></padre>
</template>

<script>
import Pare from "./components/Pare.vue";

export default {
  name: "App",
  components: {
    Pare,
  },
};
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
