<template>
  <div id="app">
    <Header></Header>
    <img alt="Vue logo" src="./assets/logo.png">
    <NavBottom msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>
import NavBottom from './components/NavBottom.vue'
import Header from './components/Header.vue'

export default {
  name: 'app',
  components: {
    NavBottom,
    Header
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  /* margin-top: 60px; */
}

* {
    margin: 0;
    padding: 0;
    text-decoration: none;
    text-align: center;
}
</style>
