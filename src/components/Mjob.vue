<template>
    <div class="container">
        <div class="t">
            <span class="t1">职位</span>
            <span class="t2">申请时间</span>
            <span class="t3">进度</span>
        </div>
        <div class="m">
            <div>
                <div>
                    <span class="name">普工</span>
                    <span class="salary">3500-4500元/月</span>
                </div>
                <span class="time">2018-05-25</span>
                <span class="note">面试通知</span>
            </div>
            <div class="b">
                <span class="b1">富士康（贵阳）</span>
                <span class="b2">南明区 机场路</span>
            </div>
        </div>
    </div>
</template>

<style scoped>
.t {
    position: relative;
    padding: 10px 0;
    font-size: 14px;
    text-align: center;
}
.t1 {
    position: absolute;
    left: 12px;
}
.t3 {
    position: absolute;
    right: 12px;
}

.m {
    padding: 10px 0 30px 0;
    border-top: 1px solid #e6e6e6;
    border-bottom: 1px solid #e6e6e6;
    margin-bottom: 10px;
    background: #fff;
    position: relative;
    text-align: center;
}
.name {
    font-size: 14px;
    position: absolute;
    left: 12px;
}

.salary {
    font-size: 13px;
    position: absolute;
    left: 12px;
    top: 30px;
}

.time {
    display: inline-block;
    font-size: 13px;
    padding: 10px 0 18px 0;
}

.note {
    font-size: 13px;
    color: #007aff;
    position: absolute;
    right: 12px;
    top: 20px;
}

.b {
    border-top: 1px dashed #e6e6e6;
    font-size: 12px;
    color: #666666;
    position: relative;
}

.b1 ,.b2 {
    display: inline-block;
    position: absolute;
    padding-top: 8px;
}

.b1 { 
    left: 12px;  
}

.b2 {
    right: 12px;  
}
</style>
