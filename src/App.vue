<template>
  <div id="app">
  <Mshare/>
  </div>
</template>

<script>
import Mshare from './components/Mshare.vue'


export default {
  name: 'app',
  components: {
    Mshare
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

.container>div {
  border-top: 1px solid #e6e6e6;
  border-bottom: 1px solid #e6e6e6;
  margin-bottom: 10px;
  background: #fff;
  position: relative;
  padding: 12px;
}

* {
  margin: 0;
  padding: 0;
  text-decoration: none;
}
</style>
