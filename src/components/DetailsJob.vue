<template>
    <div id="container">
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
                <h1>岗位说明</h1>
                <ol>
                    <li>一年的仓管经验，有工作经验者优先；</li>
                    <li>具备较强的责任心，有一定的领导能力；</li>
                    <li>懂基本的计算机操作，输出仓管文档；</li>
                    <li>严格遵守公司的制度</li>
                    <li>快速融入团队</li>    
                </ol>
            </div>
            <div class="company">
                <div>用工单位</div>
                <h2>东莞泰奇</h2>
                <p>卓伟电商是一家知名的家用电器企业，公司共有员工1500人，在广州、温州、中山等地设有分公司。</p>
            </div>
            <div class="step">
                <div>求职流程</div>
                <span>申请职位</span>
                <span class="icon"></span>
                <span>申请职位</span>
                <span class="icon"></span>
                <span>申请职位</span>
            </div>
            <div class="share">
                <span class="line"></span>
                <span>分享到</span>
                <span class="line"></span>            
                <div class="icon">
                    <span class="wechat"></span>
                    <span class="moments"></span>
                </div>
                <div class="action">
                    <button class="1">拨打电话</button>
                    <button class="1">挣推荐奖</button>
                    <button class="2">立即申请</button>
                </div>
            </div>
        </div>
    </div>
</template>

<style scoped>

.job {
    border-top: 1px solid #e6e6e6;
    border-bottom: 1px solid #e6e6e6;
    padding: 12px 12px;
}

.post {
    font-size: 20pt;
    color: black;
}

.info {
    margin-top: 7px;
}

.enterprise {
    font-size: 14pt;
    color: #4a4a4a;
}

.requirements ,.local,.welfare {
    font-size: 13pt;
    color: black;

}

.welfare  span {
    display: inline-block;
}

.tag {
    margin-bottom: 10px;
}

.tag span {
    display: inline-block;
    border: 1px solid #007aff;
    border-radius: 5px;
    padding: 3px 6px;
    font-size: 10px;
    margin-right: 6pt;
}

.reward {
    color: #f14f44;
    font-size: 13px;
    position: absolute;
    top: 57px;
    right: 12px;
}

.salary {
    display: block;
    margin: 1pt 0 20pt 0;
    color: #f14f44;
    font-size: 14pt;
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
</style>

