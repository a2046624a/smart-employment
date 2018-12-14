<template>
    <div class="container">
        <div class="qr">我是二维码</div>
        <div class="m">
            <div class="m1">
                <div class="t1">我已推荐分享</div>
                <span class="t2">51次</span>
            </div>
            <div class="m2">
                <div class="t1">我已获得奖金</div>
                <span class="t2">20400元</span>
            </div>
        </div>
        <div class="b">
            <div class="b-t">
                <span class="line"></span>
                <span class="t">邀请攻略</span>
                <span class="line"></span>
            </div>
            <div class="b-m">
                <div class="l">
                    <p>点击分享</p>
                    <p>招聘信息</p>
                </div>
                <div></div>
                <div class="m">
                    <p>好友打开链接</p>
                    <p>点击报名</p>
                </div>
                <div></div>
                <div class="r">
                    <p>好友入职</p>
                    <p>获得奖金</p>
                </div>
            </div>
            <div>
                <span  class="b-b">完成以上步骤，账户即可获得奖金</span>
            </div>
        </div>
        <input type="submit" value="马上赚赏金" class="wshare">
    </div>
</template>

<style scoped>
.qr {
    padding: 0;
    height: 150px;
}

.m1 {
    display: inline-block;
    text-align: center;
    width: 49%;
    margin-top: 12px;
    border-right: 1px solid #007aff;;
}

.t1 {
    font-size: 14px;
}

.t2{
    font-size: 24px;
    color: #007aff;;
}
.m2 {
    display: inline-block;
    text-align: center;
    width: 49%;
    margin-top: 12px;
    border-left: 1px solid #007aff;;
}

.b {
    position: relative;
    text-align: center;
}

.b-t>span {
    display: inline-block;
}

.b-m {
    border-top: 1px solid #e6e6e6;
    border-bottom: 1px solid #e6e6e6;
    position: relative;
}

.b-m>div {
    display: inline;
    /* position: absolute; */
}

.line {
    width: 32.8%;
    border-top: 3px solid #9b9b9b;
    height: 10px;
}

.t {
    font-size: 16px;
    padding: 0 19px 13px 19px;
    vertical-align: middle;
}

.l {
    position: absolute;
    left: 0;
    top: 20px;
}

.b-m>.m {
    display: inline-block;
    margin: 20px 0;
}

.r {
    position: absolute;
    right: 0;
    top: 20px;
}

.b-b {
    display: block;
    margin-top: 12px;
    font-size: 14px;
    color: #007aff;;
}

.wshare {
    appearance: none;
    border: none;
    background: #007aff;
    padding: 11px 0 11px 0;
    border-radius: 5px;
    color: #fff;
    position: fixed;
    left: 0;
    right: 0;
    width: 337px;
    bottom: 16px;
    z-index: 10;
    margin: 0 auto;
    font-size: 16px;
    text-align: center;
}

</style>
