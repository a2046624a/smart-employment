<template>
    <div id="container">
        <div class="user">
            <span class="avatar"></span>
            <span class="name">阿杜</span>
            <span class="health">健康证认证</span>
        </div>
        <div class="more">
            <a href="" class="safety">账号安全<span class="go"></span></a>
            <a href="" class="resume">我的简历<span class="go"></span></a>
            <a href="" class="wallet">我的钱包<span class="go"></span></a>
            <a href="" class="job">我的应聘<span class="go"></span></a>
            <a href="" class="train">我的培训<span class="go"></span></a>
            <a href="" class="invite">邀请好友，赚赏金奖励<span class="go"></span></a>
            <a href="" class="recruit">
                <span>我要招人</span>
                <span class="switch">切换到企业版</span>
                <span class="go"></span>
            </a>
            <a href="" class="setting">设置<span class="go"></span></a>
        </div>
    </div>
</template>
<style scoped>
.user {
    margin-top: 40px;
    margin-bottom: 10px;
    background-color: #4083FF;
    padding: 25px 0 25px 30px;
    position: relative;
    color: #fff;
}

.avatar {
    display: inline-block;
    height: 70px;
    width: 70px;
    background-color: #8e8e8e;
    border-radius: 70px;
    border: 7px solid #ffffff;
}

.name {
    font-size: 18px;
    position: absolute;
    left: 130px;
    top: 45px;
    
}

.health {
    display: inline-block;
    padding-left: 20px;
    background: url(../assets/me/healthW.png) no-repeat left; 
    background-size: 15px 15px;
    left: 130px;
    top: 75px;
    position: absolute;
}


.more {
    border-top: 1px solid #e6e6e6;
    border-bottom: 1px solid #e6e6e6;
    padding-left: 20px;
    background: #ffffff;
}

.more a {
    display: block;
    border-bottom: 1px solid #e6e6e6;
    font-size: 14px;
    padding: 15px 0 14px 34px;
    border-left: 8px solid #ffffff;
    position: relative;
    color: black;
}

.go {
    background: url(../assets/go.png) no-repeat right;
    background-size: 20px 20px;
    padding: 10px;
    position: absolute;
    right: 10px;
    top: 13px;
}

.safety {
    background: url(../assets/me/safety.png) no-repeat left;
    background-size: 25px 25px;
    padding-left: 8px;
}

.resume {
    background: url(../assets/me/resume.png) no-repeat left;
    background-size: 25px 25px;
    padding-left: 8px;
}

.wallet {
    background: url(../assets/me/wallet.png) no-repeat left;
    background-size: 25px 25px;
    padding-left: 8px;
}

.job {
    background: url(../assets/me/job.png) no-repeat left;
    background-size: 25px 25px;
    padding-left: 8px;
}

.train {
    background: url(../assets/me/train.png) no-repeat left;
    background-size: 25px 25px;
    padding-left: 8px;
}

.invite {
    background: url(../assets/me/invite.png) no-repeat left;
    background-size: 25px 25px;
    padding-left: 8px;
}

.recruit {
    background: url(../assets/me/recruit.png) no-repeat left;
    background-size: 25px 25px;
    padding-left: 8px;
}

.switch {
    color: #9b9b9b;
    position: absolute;
    right: 35px;
}

.setting {
    background: url(../assets/me/setting.png) no-repeat left;
    background-size: 25px 25px;
    padding-left: 8px;
}

</style>

