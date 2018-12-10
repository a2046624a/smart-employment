<template>
    <div class="job-info">
        <div class="info">
            <span class="job">餐厅服务员</span>
            <span class="salary">3500-4500 元/月</span>
            <div class="tag">
                <span >五险</span>
                <span>包住</span>
                <span>双休</span>
            </div>
            <button>立即申请</button>
            <span class="reward">推荐奖励 400/人</span>
        </div>
        <div class="detal">
            <span class="name">十号公馆酸菜</span>
            <span class="health">健康证认证</span>
            <span class="local">南明区 机场路</span>
        </div>
    </div>
</template>

<style scoped>
.job-info {
    height: 123px;
    margin-bottom: 12px;
    background: #ffffff;
    border-top: 1px solid #e6e6e6;
    border-bottom: 1px solid #e6e6e6;
    position: relative;
}

.info {
    margin: auto 12px; 
}

.info button {
    appearance: none;
    background: #007aff;
    color: #ffffff;
    font-size: 13px;
    padding: 7px 25px;
    border: none;
    border-radius: 5px;
    position: absolute;
    top: 15px;
    right: 12px;
}

.reward {
    color: #f14f44;
    font-size: 13px;
    position: absolute;
    top: 57px;
    right: 12px;
}

.job {
    display: block;
    margin-top: 11px;
    font-size: 14px;
    color: #1e1e1e;
}

.salary {
    display: block;
    float: left;
    margin: 5px 0 0 5px;
    left: 5px;
    color: #f14f44;
    font-size: 13px;

}

.tag {
    padding-top: 30px;
    margin-bottom: 10px;
}

.tag span {
    display: inline-block;
    border: 1px solid #007aff;
    border-radius: 5px;
    padding: 3px 6px;
    font-size: 10px;
    margin-right: 10px;
}

.detal {
    border-top: 1px dashed #e6e6e6;
    margin: auto 12px; 
    font-size: 12px;
    color: #666666;
    position: relative;
}

.name ,.local {
    display: inline-block;
    padding-top: 6px;
}

.local {
    position: absolute;
    right: 0;  
}

.health {
    display: inline-block;
    margin: auto 10px;
    padding-left: 16px;
    color: #007aff;
    text-decoration: underline;
    background: url(../assets/health.png) no-repeat left; 
    background-size: 12px 12px;
}


</style>

