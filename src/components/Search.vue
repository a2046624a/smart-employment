<template>
    <div id="search">
        <span class="locale">
            <span>贵阳</span>
            <img src="../assets/triangle.png">
        </span>
        <input type="" class="input">
        <a href="" class="button">
            <span>搜索</span>
        </a>
    </div>
</template>

<style scoped>

#search {
    margin-top: 40px;
    height: 50px;
    background: #ffffff;
    text-align: center;
}

#search .locale {
    display: inline-block;
    font-size: 18px;
    color: #1e1e1e;
    margin: 14px 0 12px 14px;
    position: absolute;
    left: 0;
}

.locale img {
    display: inline-block;
    margin-left: 7px;
}

#search .input {
    display: inline-block;
    width: 52%;
    height: 36px;
    -moz-appearance: none;
    -webkit-appearance: none;
    border: 1px solid #979797;
    margin: 8px 10px 6px 16px;
    border-radius: 5px;
}

#search .button {
    display: inline-block;
    font-size: 14px;
    color: #007aff;
    border: 1px solid #007aff;
    border-radius: 5px;
    width: 16%;
    height: 36px;
    margin: 8px 12px 6px 0;
    position: absolute;
    right: 0;
}

#search .button span {
    display: block;
    margin: 10px auto;
}
</style>

