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
import ShareJob from './components/ShareJob.vue'
import DetailsTrain from './components/DetailsTrain.vue'




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
    DetailsJob,
    ShareJob,
    DetailsTrain
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  /* padding-bottom: 65px; */
}


* {
  margin: 0;
  padding: 0;
  text-decoration: none;
}
</style>
