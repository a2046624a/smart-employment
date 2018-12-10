<template>
    <div id="header">
        <a href="" class="back">
            <img src="../assets/back.png">
            <span>返回</span>
        </a>
        <a href="" class="home">慧就业</a>
        <span></span>
        <a href="" class="more">
            <img src="../assets/more.png">
            <span></span>
        </a>
    </div>
</template>

<script>
export default {

}
</script>


<style scoped>
#header {
    height: 40px;
    width: 100%;
    text-align: center;
    position: fixed;
    top: 0;
    background: #ffffff;
    border-bottom: 1px solid #e6e6e6;
    z-index: 10;
}

#header .home {
    color: #030303;
    font-size: 17px;
    display: inline-block;
    margin: 9px 9px;
}

.back {
    position: fixed;
    left: 9px;
    top: 9px;
}

.back span {
    font-size: 17px;
    color: #007aff;
}

.more {
    position: fixed;
    right: 12px;
    top: 11px;
}
</style>

