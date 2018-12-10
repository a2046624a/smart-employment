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

<!-- 
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

  <div id="">
    <Header/>
    <DetailsJob/>
  </div>

</template>

<script>
import NavBottom from './components/NavBottom.vue'
import Header from './components/Header.vue'
import Search from './components/Search.vue'
import Banner from './components/Banner.vue'
import Jobs from './components/Jobs.vue'
import HotMore from './components/HotMore.vue'
import HotJobs from './components/HotJobs.vue'
import HotIndustry from './components/HotIndustry.vue'
import JobFilter from './components/JobFilter.vue'
import Recommend from './components/Recommend.vue'
import Expand from './components/Expand.vue'
import PerInfo from './components/PerInfo.vue'
import CheckInfo from './components/CheckInfo.vue'
import DetailsJob from './components/DetailsJob.vue'




export default {
  name: 'app',
  components: {
    NavBottom,
    Header,
    Search,
    Banner,
    Jobs,
    HotMore,
    HotJobs,
    HotIndustry,
    JobFilter,
    Recommend,
    Expand,
    PerInfo,
    CheckInfo,
    DetailsJob
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
  background: #f7f7f7;
  padding-bottom: 65px;
}

#container {
  margin-top: 40px;
  margin-bottom: 60px;
}

* {
    margin: 0;
    padding: 0;
    text-decoration: none;
    color: #030303;
}
</style>
