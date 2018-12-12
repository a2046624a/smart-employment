<template>
  <div id="app">
  <Mwallet/>
  </div>

</template>

<script>
import NavBottom from './components/NavBottom.vue'
import Header from './components/Header.vue'
import Search from './components/Search.vue'
import Banner from './components/Banner.vue'
import Mwallet from './components/Mwallet.vue'


export default {
  name: 'app',
  components: {
    NavBottom,
    Header,
    Search,
    Banner,
    Mwallet
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}

#container {
  background-color: #f7f7f7;
}

* {
  margin: 0;
  padding: 0;
  text-decoration: none;
}
</style>
