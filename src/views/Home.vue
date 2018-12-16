<template>
  <div class="home">
    <Navtop/>
    <div class="container">
      <Search/>
      <Banner/>
      <div class="tab-select">
          <span><a href="">找工作</a></span>
          <span><a href="">找培训</a></span>    
      </div>
      <div class="hot">
          <div>
              <span>热门岗位</span>
              <a href="">更多 ></a>
          </div>
          <table class="hot-jobs">
              <tr>   
                  <td><a href="">销售业务</a></td>
                  <td><a href="">销售代表</a></td>
                  <td><a href="">销售工程师</a></td>
                  <td><a href="">保安</a></td>
              </tr>
              <tr>
                  <td><a href="">客服/售后</a></td>
                  <td><a href="">客户服务</a></td>
                  <td><a href="">物业经理</a></td>
                  <td><a href="">清洁工</a></td>
              </tr>
          </table>
          <a href="" class="expand-all">
              <span>展开全部</span>
              <span class="icon"></span>
          </a>
      </div>
      <div class="hot">
          <div>
              <span>热门行业</span>
              <a href="">更多 ></a>
          </div>
          <table class="hot-industry">
              <tr>   
                  <td><a href="">互联网</a></td>
                  <td><a href="">IT服务</a></td>
                  <td><a href="">计算机硬件</a></td>
                  <td><a href="">通信/电信</a></td>
              </tr>
              <tr>
                  <td><a href="">银行</a></td>
                  <td><a href="">保险</a></td>
                  <td><a href="">物业管理</a></td>
                  <td><a href="">中介服务</a></td>
              </tr>
          </table>
          <a href="" class="expand-all">
              <span>展开全部</span>
              <span class="icon"></span>
          </a>
      </div>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
// import Login from '@/components/Login.vue'
import Navtop from '@/components/Navtop.vue'
import Search from '@/components/Search.vue'
import Banner from '@/components/Banner.vue'

export default {
  name: 'home',
  components: {
    Navtop,
    Search,
    Banner
  }
}
</script>

<style scoped>
.tab-select {
    height: 40px;
    margin-bottom: 10px;
    background: #ffffff;
}

.tab-select span {
    display: inline-block;
    text-align: center;
    width: 49%;
}

.tab-select a {
    display: inline-block;
    width: 72px;
    color: #007aff;
    padding-bottom: 10px;
    border-bottom: 2px solid #007aff;
    text-align: center;
    padding: 11px 0;
    margin: 0 auto;
    
}

.hot {
    overflow: hidden;
    border-top: 1px solid #e6e6e6;
    border-bottom: 1px solid #e6e6e6;
    margin-bottom: 10px;
    background: #ffffff;
}

.hot div {
    height: 40px;
}

.hot div span {
    float: left;
    display: block;
    margin-left: 13px;
    line-height: 40px;
}

.hot div a {
    float: right;
    font-size: 12px;
    line-height: 40px;
    color: #666;
    margin-right: 6px;
}

td {
    height: 40px;
    text-align: center;
    border:1px solid #e6e6e6;
}

td a {
    color: #1e1e1e;
    font-size: 14px;
}

table {
    border-collapse: collapse;
	width:100%;
}

.expand-all {
    width: 100%;
    height: 40px;
    line-height: 40px;
    display: inline-block;
    color: #666;
    text-align: center;
}

.expand-all .icon {
    display: inline-block;
    width: 24px;
    height: 12px;
    background: url(../assets/expand.png) no-repeat center;
}
</style>

