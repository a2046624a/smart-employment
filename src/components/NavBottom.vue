<template>
  <div id="nav-bottom">
      <a href="" class="nav-button">
          <img src="../assets/home.png">
          <span>首页</span>
      </a>
      <a href="" class="nav-button">
          <img src="../assets/job.png">
          <span>找工作</span>
      </a>
      <a href="" class="nav-button">
          <img src="../assets/train.png">
          <span>找培训</span>
      </a>
      <a href="" class="nav-button">
          <img src="../assets/me.png">
          <span>我的</span>
      </a>
  </div>
</template>

<script>
export default {

}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
#nav-bottom {
  width: 100%;
  height: 53px;
  border-top: 1px solid #e8e8e8;
  position: fixed;
  bottom: 0;
  left: 0;
  z-index: 10;
  background: #ffffff;
}

.nav-button {
  display: inline-block;
  width: 25%;
  padding-bottom: 3px;
}

.nav-button img {
  display: block;
  margin: 10px auto 7px auto;
  width: 20px;
  height: 20px;
}

.nav-button span {
  display: block;
  font-size: 10px;
  color: #596979;
  border-top: 0;
  text-align: center;
}
</style>
