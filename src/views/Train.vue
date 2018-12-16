<template>
  <div class="home">
    <Navtop/>
    <div class="container">
      <Search/>
      <Banner/>
      <div class="filter">
        <a href="">
            <span>区域</span>
            <img src="../assets/triangle.png" alt="">
        </a>
        <a href="">
            <span>类型</span>
            <img src="../assets/triangle.png" alt="">
        </a>
        <a href="">
            <span>课程</span>
            <img src="../assets/triangle.png" alt="">
        </a>
        <a href="">
            <span>更多</span>
            <img src="../assets/triangle.png" alt="">
        </a>    
      </div>
      <Recommend/>
      <ljsq/>
      <ljsq/>
      <ljsq/>
      <ljsq/>
      <a href="" class="expand">
        <span>查看更多</span>
        <span class="icon"></span>
    </a>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
// import Login from '@/components/Login.vue'
import Navtop from '@/components/Navtop.vue'
import Search from '@/components/Search.vue'
import Banner from '@/components/Banner.vue'
import Recommend from '@/components/Recommend.vue'
import ljsq from '@/components/ljsq.vue'

export default {
  name: 'home',
  components: {
    Navtop,
    Search,
    Banner,
    Recommend,
    ljsq
  }
}
</script>

<style scoped>
.filter {
    height: 44px;
    background: white;
    border-bottom: 1px solid #e6e6e6;
    position: relative;
    margin-bottom: 10px;

}

.filter a {
    display: inline-block;
    padding: 12px 0px;
    width: 25%;
    text-align: center;
    font-size: 16px;
    color: #000;
}

.filter img {
    position: absolute;
    margin-left: 4px;
}

.expand {
    width: 100%;
    height: 40px;
    line-height: 40px;
    display: inline-block;
    color: #666;
    text-align: center;
    background: #ffffff;
    border-bottom: #e6e6e6;
}

.expand>.icon {
    display: inline-block;
    width: 24px;
    height: 12px;
    background: url(../assets/expand.png) no-repeat center;
}

</style>
