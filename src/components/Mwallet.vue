<template>
    <div class="container">
        <div class="winfo">
            <div class="w1">
                <div class="wtag">可提现</div>
                <span class="wmoney1">￥ 88.56</span>
            </div>
            <div class="w2">
                <div class="w21">
                    <div class="wtag">冻结返费</div>
                    <span>￥ 0.00</span>
                </div>
                <div class="w22">
                    <div class="wtag">已提现</div>
                    <span>￥ 105.00</span>
                </div>
            </div>
        </div>
        <div class="wtips">
            <p><span>友情提示：</span>当邀请好友未完成出发进厂时，厂区奖金有变动，冻结返费跟随变动，请悉知！</p>
        </div>

        <a href="" class="wbank">
                <span>银行卡卡绑定</span>
                <span class="wbn">未绑定</span>
                <span class="go"></span>
        </a>
        <van-tabs v-model="active" color="#4886ff" class="wtab">
            <van-tab title="冻结返费">
                <div class="w-info">
                    <h1>首次注册</h1>
                    <h2>2018-06-30 18:58:32</h2>
                    <h3>+￥99999.99</h3>
                </div>
                <div class="w-info">
                    <h1>首次注册</h1>
                    <h2>2018-06-30 18:58:32</h2>
                    <h3>+￥99999.99</h3>
                </div>
                <div class="w-info">
                    <h1>首次注册</h1>
                    <h2>2018-06-30 18:58:32</h2>
                    <h3>+￥99999.00</h3>
                </div>
                <div class="w-info">
                    <h1>首次注册</h1>
                    <h2>2018-06-30 18:58:32</h2>
                    <h3>+￥99999.00</h3>
                </div>
                <div class="w-info">
                    <h1>首次注册</h1>
                    <h2>2018-06-30 18:58:32</h2>
                    <h3>+￥99999.00</h3>
                </div>
                <div class="w-info">
                    <h1>首次注册</h1>
                    <h2>2018-06-30 18:58:32</h2>
                    <h3>+￥99999.00</h3>
                </div>
                <div class="w-info">
                    <h1>首次注册</h1>
                    <h2>2018-06-30 18:58:32</h2>
                    <h3>+￥99999.00</h3>
                </div>
            </van-tab>
            <van-tab title="可提明细">
                <div class="w-info">
                    <h1>首次注册</h1>
                    <h2>2018-06-30 18:58:32</h2>
                    <h3>+￥99999.99</h3>
                </div>
                <div class="w-info">
                    <h1>首次注册</h1>
                    <h2>2018-06-30 18:58:32</h2>
                    <h3>+￥99999.99</h3>
                </div>
            </van-tab>
            <van-tab title="提现记录">
                <div class="w-info">
                    <h1>首次注册</h1>
                    <h2>2018-06-30 18:58:32</h2>
                    <h3>+￥99999.99</h3>
                </div>
            </van-tab>
        </van-tabs>
        <input type="submit" value="申请提现" class="wcash">
    </div>
</template>

<style>
.winfo {
    background-color: #4083ff;
    padding: 40px 12px 12px 12px;
    color: #fff;
    margin-bottom: 10px;
}
.w1 {
    text-align: center;
    height: 100px;
    border-bottom: 3px solid #fff;
}

.w1>span {
    font-size: 40px;
    
}

.w21 {
    display: inline-block;
    text-align: center;
    width: 49%;
    margin-top: 12px;
    border-right: 1px solid #fff;
}

.w22 {
    display: inline-block;
    text-align: center;
    width: 49%;
    margin-top: 12px;
    border-left: 1px solid #fff;
}

.w2 span {
    font-size: 20px;
    line-height: 30px;
}

.wtag {
    font-size: 12px;
    text-align: center;
    padding: 5px 23px;
    display: block;
    background-color: #1d60db;
    border-radius: 15px;
    width: 55px;
    margin: auto;
}

.wtips {
    font-size: 13px;
    border-top: 1px solid #e6e6e6;
    border-bottom: 1px solid #e6e6e6;
    padding: 12px;
    margin-bottom: 10px;
    background: #fff;
    line-height: 150%;
}

.wtips>p>span {
    color: #f14f44;
}

.wbank {
    display: block;
    border-bottom: 1px solid #e6e6e6;
    font-size: 14px;
    padding: 15px 0 14px 5px;
    border-left: 8px solid #ffffff;
    position: relative;
    color: black;
    background: #fff;
    margin-bottom: 10px;
}

.wbank>.go {
    background: url(../assets/go.png) no-repeat right;
    background-size: 20px 20px;
    padding: 10px;
    position: absolute;
    right: 10px;
    top: 13px;
}

.wbn {
    color: #9b9b9b;
    position: absolute;
    right: 35px;
}

.wtab {
    border-top: 1px solid #e6e6e6;
    border-bottom: 1px solid #e6e6e6;
    padding: 44px 12px 0 12px;
    background: #fff;
}

.van-tabs__wrap {
    border-bottom: 1px solid #e6e6e6 !important;
}

.van-tab {
    font-size: 16px !important;
    color: #000 !important;
}

.van-tab--active {
    color: #007aff !important;
}


.w-info {
    border-top: 1px solid #e6e6e6;
    padding: 8px 0 6px 0;
    position: relative;
}

.w-info>h1 {
    font-size: 14px;
}

.w-info>h2 {
    font-size: 10px;
    color: #4a4a4a;
}

.w-info>h3 {
    display: inline-block;
    font-size: 14px;
    position: absolute;
    top: 12px;
    right: 25px;
}

.wcash {
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


<script>
export default {
    data() {
        return {
            active: 0
        };
    }
}
</script>
