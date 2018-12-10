<template>
    <div class="recommend">
        <div>
            <span>热门推荐</span>
            <a href="">更多 ></a>
        </div>
        <table class="rd">
            <tr>
                <td>
                    <a href="">
                        <img src="" alt="">
                        <p class="name">富士康集团</p>
                        <p class="describe">普工 多名</p>
                    </a>
                </td>
                <td>
                    <a href="">
                        <img src="" alt="">
                        <p class="name">富士康集团</p>
                        <p class="describe">普工 多名</p>
                    </a>
                </td>
                <td>
                    <a href="">
                        <img src="" alt="">
                        <p class="name">富士康集团</p>
                        <p class="describe">普工 多名</p>
                    </a>
                </td>
            </tr>
        </table>
    </div>
</template>

<style scoped>

.recommend {
    border-top: 1px solid #e6e6e6;
    border-bottom: 1px solid #e6e6e6;
    margin-bottom: 10px;
    background: #ffffff;
    padding-bottom: 10px;
}

.recommend div {
    height: 40px;
    border-bottom: 1px solid #e6e6e6;
}

.recommend div span {
    float: left;
    display: block;
    margin-left: 13px;
    line-height: 40px;
}

.recommend div a {
    float: right;
    font-size: 12px;
    line-height: 40px;
    color: #666;
    margin-right: 6px;
}

table {
    border-collapse: collapse;
	width:100%;
}

td {
    width: 33.33%;
    text-align: center;
    border: none;
}

img {
    display: block;
    width: 107px;
    height: 58px;
    background: blueviolet;
    margin: 20px auto 10px auto;
}

.name {
    font-size: 14px;
    color: #1e1e1e;
}

.describe {
    font-size: 13px;
    color: #666666;
}

p {
    line-height: 150%;
}

</style>

