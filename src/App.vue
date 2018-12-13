<template>
  <div id="app">
  <Mjob/>
  </div>

</template>

<script>
import NavBottom from './components/NavBottom.vue'
import Header from './components/Header.vue'
import Search from './components/Search.vue'
import Banner from './components/Banner.vue'
import Mjob from './components/Mjob.vue'


export default {
  name: 'app',
  components: {
    NavBottom,
    Header,
    Search,
    Banner,
    Mjob
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}

.container {
  background-color: #f7f7f7;
  margin-top: 40px;
}

* {
  margin: 0;
  padding: 0;
  text-decoration: none;
}
</style>
