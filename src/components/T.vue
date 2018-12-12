<template>
    <div>
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
    </div>
</template>

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
</style>
