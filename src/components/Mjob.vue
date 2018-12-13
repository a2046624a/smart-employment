<template>
    <div class="container">
        <div class="t">
            <span>职位</span>
            <span>申请时间</span>
            <span>进度</span>
        </div>
        <div class="mj-info">
            <div>
                <span class="name">普工</span>
                <span class="salary">3500-4500元/月</span>
            </div>
            <span class="time">2018-05-25</span>
            <span class="note">面试通知</span>
            <div class="detal">
                <span class="name">十号公馆酸菜</span>
                <span class="local">南明区 机场路</span>
            </div>
        </div>

    </div>
</template>

<style scoped>
.t {
    text-align: center;
}

.mj-info {
    padding: 12px;
    border-top: 1px dashed #e6e6e6;
    border-bottom: 1px dashed #e6e6e6;
    margin-bottom: 10px;
    background: #fff;
}
.name {
    font-size: 14px;
}

.salary {
    font-size: 13px;
}

.time {
    font-size: 13px;
}

.note {
    font-size: 13px;
    color: #007aff;
}

.detal {
    border-top: 1px dashed #e6e6e6;
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
</style>
