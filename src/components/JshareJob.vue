<template>
    <div>
        <div class="mask"></div>
        <div class="per-info">
            <a href="" class="close"></a>
            <span class="t">分享工作</span>
            <div class="contain">
                <p>将职位信息分享至好友或朋友圈，好友申请职位并入职后可获得奖金。</p>
                <input type="submit" value="分享工作 赚赏金" class="next">
            </div>
        </div>
    </div>
</template>

<style scoped>
.contain {
    padding: 15px 25px;
}

p {
    text-align: justify;
    font-size: 14px;
    line-height: 150%;
}

.mask {
    position: fixed;
    top: 0;
    width: 100%;
    height: 100%;  
    background: #000000;
    opacity: 0.7;
    z-index: 11;
}

.per-info {
    position: fixed;
    top: 239px;
    margin: auto 37px;
    width: 80%;
    height: 190px;
    background: #ffffff;
    border-radius: 5px;
    z-index: 12;
    text-align: center;
    color: #030303;
}

.per-info .t {
    font-size: 16px;
    color: #030303;
    display: inline-block;
    width: 100%;
    padding: 16px 0 12px 0;
    border-bottom: 1px solid #e6e6e6;
    
}

.close {
    display: inline-block;
    background: url(../assets/close.png) no-repeat center;
    padding: 20px 20px;
    position: absolute;
    top: 3px;
    right: 12px;  
}

.next {
    appearance: none;
    border: none;
    background: #007aff;
    padding: 11px 66px;
    border-radius: 5px;
    margin-top: 13px;
    font-size: 16px;
    color: white;
}

</style>
