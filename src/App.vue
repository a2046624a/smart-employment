<template>
  <div id="app">
    <Header></Header>
    <Search></Search>
    <Banner></Banner>
    <Jobs></Jobs>
    <NavBottom msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>
import NavBottom from './components/NavBottom.vue'
import Header from './components/Header.vue'
import Search from './components/Search.vue'
import Banner from './components/Banner.vue'
import Jobs from './components/Jobs.vue'

export default {
  name: 'app',
  components: {
    NavBottom,
    Header,
    Search,
    Banner,
    Jobs
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
  background: #f7f7f7;
  /* margin-top: 60px; */
}

* {
    margin: 0;
    padding: 0;
    text-decoration: none;
    text-align: center;
}
</style>
