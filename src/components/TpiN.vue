<template>
    <div>
        <div class="mask"></div>
        <div class="per-info">
            <span class="close"></span>
            <span class="t">请完善个人信息</span>
            <div class="contan">
                <span>手机号</span>
                <input type="tel" value="请输入手机号">
                <a href="">获取验证码</a>
            </div>
            <div class="contan">
                <span>验证码</span>
                <input type="tel" value="请输入手机验证码">
            </div>
            <div class="contan">
                <span>姓名</span>
                <input type="text" value="请输入真实姓名">
            </div>
            <input type="submit" value="下一步" class="next">
        </div>
    </div>
</template>

<style scoped>
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
    top: 0;
    left: 0;
    bottom: 0;
    right: 0;
    margin: auto;
    width: 80%;
    height: 290px;
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
    margin: 24px auto 10px auto;
    
}

.close {
    display: inline-block;
    background: url(../assets/close.png) no-repeat center;
    padding: 20px 20px;
    position: absolute;
    top: 13px;
    right: 12px;  
}

.contan {
    margin: 0 24px;
    height: 45px;
    font-size: 14px;
    border-bottom: 1px solid #b2b2b2;
    position: relative;
}

.contan span { 
    position: absolute;
    bottom: 12px;
    left: 0;
}

.contan a {  
    position: absolute;
    bottom: 12px;
    right: 0;
    color: #007aff;
}

.contan input {
    appearance: none;
    position: absolute;
    bottom: 13px;
    left: 65px;
    border: none;
    color: #9b9b9b;
    width: 110px;
}

.next {
    appearance: none;
    border: none;
    background: #007aff;
    padding: 12px 100px;
    border-radius: 5px;
    margin: 23px 0 32px 0;
}

</style>
