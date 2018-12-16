<template>
    <van-tabbar v-model="active">
        <van-tabbar-item info="" to="/">
            <span>首页</span>
            <img
            slot="icon"
            slot-scope="props"
            :src="props.active ? home.active : home.normal"
            >
        </van-tabbar-item>
        <van-tabbar-item info="" to="/job">
            <span>找工作</span>
            <img
            slot="icon"
            slot-scope="props"
            :src="props.active ? hire.active : hire.normal"
            >
        </van-tabbar-item>
        <van-tabbar-item info="" to="/train">
            <span>找培训</span>
            <img
            slot="icon"
            slot-scope="props"
            :src="props.active ? processing.active : processing.normal"
            >
        </van-tabbar-item>
        <van-tabbar-item info="" to="/me">
            <span>我的</span>
            <img
            slot="icon"
            slot-scope="props"
            :src="props.active ? me.active : me.normal"
            >
        </van-tabbar-item>
    </van-tabbar>
</template>

<script>
export default {
  data() {
    return {
      active: 0,
      home: {
        normal: require('../assets/icon/navbot/home-nor.png'),
        active: require('../assets/icon/navbot/home-act.png')
      },
      hire: {
        normal: require('../assets/icon/navbot/job-nor.png'),
        active: require('../assets/icon/navbot/job-act.png')
      },
      processing: {
        normal: require('../assets/icon/navbot/train-nor.png'),
        active: require('../assets/icon/navbot/train-act.png')
      },
      me: {
        normal: require('../assets/icon/navbot/me-nor.png'),
        active: require('../assets/icon/navbot/me-act.png')
      }
    }
  }
}
</script>
