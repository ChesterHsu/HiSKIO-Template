<template>
  <div>
    <div class="carousel">
      <a href="#">
        <img src="@/assets/images/carousel.png">
      </a>
    </div>
    <div class="hotTags">
      <div class="tagsTitle">
        <button>遊戲開發</button>
        <button>微軟產品</button>
        <button>電腦科學</button>
        <button>桌面應用</button>
        <button>人工智慧</button>
        <button>維運/測試</button>
        <button>雲端服務</button>
        <button>資訊安全</button>
        <button>程式交易</button>
      </div>
      <hr>
      <div class="tagsBody">
        <p>熱門標籤</p>
        <button>PHP</button>
        <button>C/C++</button>
        <button>Arduino</button>
        <button>R 語言</button>
        <button>JavaScript</button>
        <button>SVG</button>
        <button>Data Visualization</button>
        <button>HTML</button>
        <button>Python</button>
        <button>Python 3</button>
      </div>
    </div>
    <div class="content">

    </div>
  </div>
</template>

<script>

export default {

}
</script>
<style scoped>
.carousel{
  width: 100%;
  height: 536px;
  margin-bottom: 163px;
}
.hotTags{
  width: 1100px;
  height: 169px;
  position: absolute;
  left: 50%;
  transform: translate(-50%, -140%);
  border-radius: 5px;
  box-shadow:1px 3px 9px gray;
  background: #ffffff;
}
.hotTags .tagsTitle{
  width: 1000px;
  padding-left: 50px;
  padding-right: 50px;
  height: 67px;
}
.hotTags .tagsTitle button{
  font-size: 17px;
  height: 67px;
  background-color: #ffffff; /* Green background */
  border: 1px solid #ffffff; /* Green border */
  padding: 9px 20px; /* Some padding */
  cursor: pointer; /* Pointer/hand icon */
  float: left;
}
.hotTags .tagsBody{
  width: 1000px;
  padding-left: 50px;
  padding-right: 50px;
  height: 100px;
}
.hotTags .tagsBody p{
  margin: 42px 16px 42px 0px;
  float: left;
  color: #8c8c8c;
}
.hotTags .tagsBody button{
  height: 37px;
  margin: 31px 16px 31px 0px;
  padding: 8px;
  border:none;
  border-radius: 5px;
  color: #428da9;
  font-size: 10px;
  float: left;
}
.content{
  width: 872px;
  height: 63px;
  margin: 0px auto 72px;
  background: url("./assets/images/content.png") no-repeat left center;
}
</style>

