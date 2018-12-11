<template>
    <div class="job-details">
        <div class="job">
            <div class="post">仓管员</div>
            <div class="info">
                <span class="enterprise">东莞泰奇</span>
                <span class="health">健康证认证</span>
            </div>
            <div class="salary">30001-5000元/月</div>
            <div class="requirements">要求：招5人/大专/一年仓管经验</div>
            <div class="local">地址：广州市-花都区-花东镇</div>
            <div class="welfare">
                <span>福利：</span>
                <div class="tag">
                    <span>包吃</span>
                    <span>包住</span>
                    <span>五险</span>
                </div>
            </div>
            <div class="reward">推荐奖励 400/人</div>
        </div>
        <div class="description">
            <div class="tt">岗位说明</div>
            <p>
            1.一年的仓管经验，有工作经验者优先；<br>
            2.具备较强的责任心，有一定的领导能力；<br>
            3.懂基本的计算机操作，输出仓管文档；<br>
            4.严格遵守公司的制度<br>
            5.快速融入团队<br>
            </p>
            <a href="" class="expand">
                <span>展开信息</span>
                <span class="icon"></span>
            </a>
        </div>
        <div class="company">
            <div class="tt">用工单位</div>
            <h2>东莞泰奇</h2>
            <p>卓伟电商是一家知名的家用电器企业，公司共有员工1500人，在广州、温州、中山等地设有分公司。</p>
            <a href="" class="expand">
                <span>展开信息</span>
                <span class="icon"></span>
            </a>
        </div>
        <div class="step">
            <div class="tt">求职流程</div>
            <span>申请职位</span>
            <span >>></span>
            <span>企业查看</span>
            <span >>></span>
            <span>确认入职</span>
        </div>
        <div class="share">
            <span class="line"></span>
            <span class="to">分享到</span>
            <span class="line"></span>            
            <div class="icon">
                <span class="wechat"></span>
                <span class="moments"></span>
            </div>
            <div class="action">
                <button class="b1">拨打电话</button>
                <button class="b1">挣推荐奖</button>
                <button class="b2">立即申请</button>
            </div>
        </div>
    </div>
</template>

<style scoped>

.job-details {
    margin-top: 40px;
    background: #f7f7f7;
}

.expand {
    width: 100%;
    height: 40px;
    line-height: 40px;
    display: inline-block;
    color: #666;
    text-align: center;
    background: #ffffff;
    border-bottom: #e6e6e6;
    border-top: 1px solid #e6e6e6;
    margin-top: 6px;
    font-size: 14px;
}

.expand .icon {
    display: inline-block;
    width: 24px;
    height: 12px;
    background: url(../assets/expand.png) no-repeat center;
}

.company h2 {
    font-size: 13px;
    font-weight: bold;
}

h2 {
    margin-bottom: 2px;
}

p {
    line-height: 150%;  
}

.job,.description,.company,.step,.share {
    border-top: 1px solid #e6e6e6;
    border-bottom: 1px solid #e6e6e6;
    padding: 12px 12px 0 12px;
    margin-bottom: 10px;
    background: white;
}

.post {
    font-size: 20px;
    color: black;
    font-weight: bolder;
}

.info {
    margin-top: 7px;
}

.enterprise {
    font-size: 14px;
    color: #4a4a4a;
}

.requirements ,.local,.welfare {
    font-size: 13px;
    color: black;
    margin-bottom: 5px;

}

.welfare {
    margin-bottom: 10px;
}

.welfare  span {
    display: inline-block;
    vertical-align: middle;
}

.tag {
    display: inline-block;
}

.tag span {
    display: inline-block;
    border: 1px solid #007aff;
    border-radius: 2px;
    color: #007aff;
    padding: 3px 6px;
    font-size: 10px;
    margin-right: 6px;
}

.reward {
    color: #f14f44;
    font-size: 14px;
    position: absolute;
    top: 57px;
    right: 12px;
}

.salary {
    display: block;
    margin: 3px 0 20px 0;
    color: #f14f44;
    font-size: 14px;
}

.name {
    display: inline-block;
    padding-top: 6px;
}

.health {
    display: inline-block;
    margin-left: 15px;
    padding-left: 16px;
    color: #007aff;
    text-decoration: underline;
    background: url(../assets/health.png) no-repeat left; 
    background-size: 12px 12px;
}


.tt {
    font-size: 14px;
    font-weight: bold;
    border-bottom: 1px solid #e6e6e6;
    padding-bottom: 15px;
    margin-bottom: 9px;
}

.step {
    padding-bottom: 12px;
}

.step span {
    font-size: 14px;
    display: inline-block;
    font-weight: bold;
    margin-right: 15px;
}

.share {
    text-align: center;
    padding: 12px 0 0 0;
    margin: 0;
}

.share span {
    display: inline-block;
    text-align: center;
}

.line {
    border-bottom: 3px solid #e6e6e6;
    width: 30%;
}

.to {
    font-size: 16px;
    font-weight: lighter;
    margin: 0 27px;
    vertical-align: middle;
}

.share .icon {
    text-align: center;
}

.wechat {
    background: url(../assets/wechat.png) no-repeat center;
    width: 64px;
    height: 64px;
    margin: 15px;
}

.moments {
    background: url(../assets/moments.png) no-repeat center;
    width: 64px;
    height: 64px;
    margin: 15px;
}

.action {
    height: 60px;
    border-top: 2px solid #e6e6e6;
}

.b1 {
    appearance: none;
    font-size: 16px;
    padding: 9px 13px;
    border: #007aff 1px solid;
    color: #007aff;
    background: #ffffff;
    margin: 10px 10px 10px 0;
}

.b2 {
    appearance: none;
    font-size: 16px;
    padding: 9px 42px;
    border: none;
    color: white;
    background: #007aff;
}

</style>

