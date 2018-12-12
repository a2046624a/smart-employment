<template>
    <div>
        <div class="mask"></div>
        <div class="per-info">
            <a href="" class="close"></a>
            <span class="t">请核实个人信息</span>
            <div class="contan">
                <span>手机号</span>
                <input type="tel" value="18018001818">
                <a href="">获取验证码</a>
            </div>
            <div class="contan">
                <span>姓名</span>
                <input type="text" value="阿杜">
            </div>
            <div class="contan">
                <span>生日</span>
                <span class="expand"></span>
            </div>

            <div class="contan">
                <span>性别</span>
                <select name="sex">
                    <option value="male">男</option>
                    <option value="female">女</option>
                </select>
            </div>

            <div class="detal">
                <div class="icon"></div>
                <span>已自动生成简历</span>
                <a href="">查看</a>
            </div>

            <a href="" class="share">分享奖励</a>
            <input type="submit" value="发送申请" class="next">
        </div>
        <!-- <div class="success">
            <a href="" class="close"></a>
            <span class="t">申请成功</span>
            <p>您的申请已提交，企业以电话的方式通知您面试入职，请保持电话畅通。</p>
        </div> -->
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
    top: 143px;
    margin: auto 37px;
    width: 80%;
    background: #ffffff;
    border-radius: 5px;
    z-index: 12;
    text-align: center;
    color: #030303;
}

.t {
    font-size: 16px;
    display: inline-block;
    vertical-align: middle;
    margin: 24px 0 10px 0;
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
    display: inline-block;
    border: none;
    background: #007aff;
    padding: 12px 28px;
    border-radius: 5px;
    font-size: 16px;
    color: #ffffff;
    margin-left: 5px;
    margin-bottom: 22px;
}

select {
    border: none;
    position: absolute;
    bottom: 13px;
    width: 30%;
    right: 0; 
}

.success {
    position: fixed;
    top: 263px;
    margin: auto 37px;
    width: 80%;
    background: #ffffff;
    border-radius: 5px;
    z-index: 13;
    text-align: center;
}

.success p {
    margin: 27px 24px 20px 24px;
    font-size: 14px;
}



.share {
    display: inline-block;;
    border: #007aff 1px solid;
    border-radius: 5px;
    padding: 12px 28px;
    font-size: 16px;
    color: #007aff;
    margin-right: 5px;

}

.detal {
    padding-top: 14px;
    text-align: center;
    margin-bottom: 18px;
}
.detal .icon {
    display: inline-block;
    width: 18px;
    height: 18px;
    border-radius: 18px;
    background: #007aff;
    vertical-align: middle;
}

.detal span {
    font-size: 14px;
    color: #030303;
    display: inline-block;
    margin: 0 12px;
    margin-top: 2.5px;
    vertical-align: middle;
}

.detal a {
    display: inline-block;
    border: 1px solid #007aff;
    border-radius: 2px;
    padding: 2px 14px;
    font-size: 10px;
    color: #007aff;

}


</style>
