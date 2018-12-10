<template>
    <div>
        <div class="go-back">
            <a href="">
                <span>返回上一级</span>
            </a>
        </div>
        <div class="job-category">
            <span>服务员</span>
        </div>
    </div>
</template>


<script>
export default {
    
}
</script>


<style scoped>
.go-back {
    margin-top: 40px;
    border-bottom: 1px solid #e6e6e6;
    background: #ffffff;
}

.go-back a {
    display: inline-block;
    font-size: 12px;
    margin-left: 18px; 
    padding: 14px;
    color: #000;
    background: url(../assets/go-back.png) no-repeat center left;
}

.go-back span {
    display: inline-block;
    margin-left: 10px;
}

.job-category span {
    display: inline-block;
    font-size: 14px;
    margin: 12px auto 12px 17px;
}

</style>

