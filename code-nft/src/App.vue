<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <HeaderMenu />
  </div>
</template>

<script>
import HeaderMenu from './components/HeaderMenu.vue'

export default {
  name: 'App',
  components: {
    HeaderMenu
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
  background: #07070C !important;
  margin: 0;
  padding: 0;
}
</style>
