<template>
<!-- Home
  <div id="app">
    <Header/>
    <Search/>
    <Banner/>
    <Jobs/>
    <NavBottom/>
  </div>
-->

<!-- HotJobs
  <div id="app">
    <Header></Header>
    <HotMore/>
    <HotJobs/>
    <HotJobs/>
    <HotJobs/>
    <HotJobs/>
    <HotJobs/>
    <HotJobs/>
  </div> 
-->
  
<!-- HotIndustry
  <div id="app">
    <Header></Header>
    <HotMore/>
    <HotIndustry/>
    <HotIndustry/>
    <HotIndustry/>
    <HotIndustry/>
    <HotIndustry/>
    <HotIndustry/>
    <HotIndustry/>
    <HotIndustry/>
  </div> 
-->

<!-- PerInfo
    <div id="app">
    <NavBottom/>
    <Header/>
    <Search/>
    <Banner/>
    <JobFilter/>
    <Recommend/>
    <HotJobs/>
    <HotJobs/>
    <HotJobs/>
    <Expand/>
    <PerInfo/>
    <CheckInfo/>
  </div> 
-->

<!-- DetailsJob
  <div id="">
    <Header/>
    <DetailsJob/>
  </div> 
-->

<!-- ShareJob
  <div id="app">
    <ShareJob/>
  </div> 
-->

<!-- DetailsTrain
    <div id="app">
    <Header/>
    <DetailsTrain/>
  </div> 
-->
  <div id="app">
    <TpiN/>
  </div>

</template>

<script>
import NavBottom from './components/NavBottom.vue'
import Header from './components/Header.vue'
import Search from './components/Search.vue'
import Banner from './components/Banner.vue'
import TpiN from './components/TpiN.vue'




export default {
  name: 'app',
  components: {
    NavBottom,
    Header,
    Search,
    Banner,
    TpiN
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}


* {
  margin: 0;
  padding: 0;
  text-decoration: none;
}
</style>
