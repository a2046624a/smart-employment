<template>
    <div class="container">
        <div class="t">
            <span class="t1">课程</span>
            <span class="t2">申请时间</span>
            <span class="t3">进度</span>
        </div>
        <div class="m">
            <span class="t1">电工培训</span>
            <span class="t2">2018-05-25</span>
            <span class="t3">已申请</span>
            <div class="b">
                <span class="b1">直通教育</span>
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

.m>.t3 {
    color: #007aff;
}

.b {
    border-top: 1px dashed #e6e6e6;
    font-size: 12px;
    color: #666666;
    position: relative;
    margin-top: 10px;
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
