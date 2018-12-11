<template>
    <div class="job-details">
        <div class="job">
            <div class="post">高级厨师长</div>
            <div class="tag">直通教育</div>
            <div class="info">
                <p>授课形式：线下课程</p>
                <p>开课班型：全日制 晚班制 周末班</p>
                <p>上课地点：南阳分校 小河分校 白云分校</p>
                <p>课程特色：实战技能 推荐就业 包学包会</p>
            </div>
        </div>

        <div class="introduction">
            <div class="tt">课程简介</div>
            <div class="content">图文</div>
            <a href="" class="expand">
                <span>展开信息</span>
                <span class="icon"></span>
            </a>
        </div>
        <div class="company">
            <div class="tt">机构简介</div>
            <h2>直通教育</h2>
            <p>直通教育2010年成立，在南阳、小河等区域设置分校，2012年获得“最佳机构”称号<br>地址：南阳区中山路36号
            </p>
            <a href="" class="expand">
                <span>展开信息</span>
                <span class="icon"></span>
            </a>
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
                <button class="b1">电话咨询</button>
                <button class="b3">分享</button>
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

.job,.company,.introduction,.share {
    border-top: 1px solid #e6e6e6;
    border-bottom: 1px solid #e6e6e6;
    padding: 15px 12px 0 12px;
    margin-bottom: 10px;
    background: white;
}

.post {
    font-size: 18px;
    color: black;
    font-weight: bolder;
}

.tag {
    font-size: 13px;
    color: #007aff;
    margin: 5px 0;
}

.info {
    font-size: 13px;
    line-height: 200%;
    margin-bottom: 15px;
}

.tt {
    font-size: 14px;
    font-weight: bold;
    border-bottom: 1px solid #e6e6e6;
    padding-bottom: 15px;
    margin-bottom: 9px;
}

.content {
    height: 400px;
    font-size: 72px;
    text-align: center;
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

.b3 {
    appearance: none;
    font-size: 16px;
    padding: 9px 29px;
    border: #007aff 1px solid;
    color: #007aff;
    background: #ffffff;
    margin: 10px 10px 10px 0;
}

</style>

