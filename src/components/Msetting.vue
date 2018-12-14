<template>
    <div class="container">
        <a href="">账号安全<span class="go"></span></a>
        <a href="">我的简历<span class="go"></span></a>
        <a href="">我的钱包<span class="go"></span></a>
        <span>
            <div class="t">意见反馈</div>
            <p>您的宝贵建议，是我们追求极致服务的强大动力，请输入您的建议：</p>
            <textarea name="" class="se"></textarea>
        </span>
        <input type="submit" value="退出登录" class="logout">
    </div>
</template>

<style scoped>
.container {
    padding: 0 12px;
    background: #ffffff;
    border-top: 1px solid #e6e6e6;
    border-bottom: 1px solid #e6e6e6;
}

.container>a {
    display: block;
    border-bottom: 1px solid #e6e6e6;
    font-size: 14px;
    padding: 15px 0 14px 0;
    border-left: 8px solid #ffffff;
    position: relative;
    color: black;
    background: #ffffff;
}
.go {
    background: url(../assets/go.png) no-repeat right;
    background-size: 20px 20px;
    padding: 10px;
    position: absolute;
    right: 0;
    top: 13px;
}

span {
    display: block;
    padding: 15px 8px;
}

.t {
    font-size: 14px;
    margin-bottom: 10px;
}

p {
    font-size: 12px;
    color: #4a4a4a;
    line-height: 150%;
}

.se {
    display: block;
    height: 100px;
    width: 334px;
    border: 1px solid #e6e6e6;
    margin-top: 10px;
}

.logout {
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
    margin: auto;
    font-size: 16px;
    text-align: center;
}


</style>
