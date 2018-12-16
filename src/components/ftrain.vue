<template>
    <div class="job-info">
        <div class="info">
            <span class="job">电工</span>
            <span class="salary">线下课程</span>
            <div class="tag">
                <span >实战技能</span>
                <span>推荐就业</span>
                <span>包学包会</span>
            </div>
            <button>立即申请</button>
        </div>
        <div class="detal">
            <span class="name">直通教育</span>
            <span class="local">南明分校</span>
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

.job {
    display: block;
    margin-top: 11px;
    font-size: 14px;
    color: #1e1e1e;
}

.salary {
    display: block;
    float: left;
    margin: 5px 0 0 0;
    color: #f14f44;
    font-size: 13px;
}

.tag {
    padding-top: 30px;
    margin-bottom: 10px;
    color: #007aff;
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

</style>

