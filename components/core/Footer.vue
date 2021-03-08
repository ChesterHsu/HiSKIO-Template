<template>
  <div class="footer">
    <div class="section1">
      <div class="view1">
        <input class="goToFaceBook" type="button">
      </div>
    </div>
    <div class="section2">
      <ul>
        <li><a href="#">講師招募</a></li>
        <li><a href="#">常見問題</a></li>
        <li><a href="#">隱私權條款</a></li>
        <li><a href="#" style="margin-right: 0px">使用者條款</a></li>
      </ul>
    </div>
    <div class="section3">
      <p>Copyright&ensp;2020&ensp;HiSKIO</p>
    </div>
  </div>
</template>

<script>
import Index from "~/pages";
export default {
  name: "Footer",
  components: {Index}
}
</script>

<style scoped>
 .footer{
   width: 100%;
   height: 180px;
   background: #414243;
 }
 .footer .section1{
   width: 172px;
   height: 33px;
   padding: 40px 0px 45px 0px;
   margin: 0px auto;
 }
 .footer .section1 .view1{
   width: 172px;
   height: 33px;
 }
 .footer .section1 .view1 .goToFaceBook{
   width: 172px;
   height: 33px;
   border: none;
   background: url("./assets/images/goToFaceboookBtn.png") no-repeat left center;
   border: none;
 }
 .footer .section2{
   width: 580px;
   height: 20px;
   margin: 0px auto 18px;
 }
 .footer .section2 ul li{
   font-size: 14px;
   list-style-type:none;
   float: left;
   border: none;
 }
 .footer .section2 ul li a{
   text-decoration:none;
   float: left;
   margin-right: 109px;
   color: #fbfbfb;
 }
 .footer .section3{
   width: 148px;
   height: 18px;
   margin: 0 auto;
 }
 .footer .section3 p{
   color: #fbfbfb;
   font-size: 13px;
 }
</style>
