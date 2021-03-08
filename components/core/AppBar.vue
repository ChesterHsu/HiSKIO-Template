<template>
  <div id="header">
    <div class="logo">
      <a href="#">
        <img src="@/assets/images/logo.png">
      </a>
    </div>
    <div class="search">
      <form>
        <input class="searchButton" type="submit" value="">
        <input class="text" type="text" value="搜尋">
      </form>
    </div>
    <div class="flexRight">
      <div class="teach">
        <a href="#">我想開課</a>
      </div>
      <div class="shoppingCar">
        <input class="shoppingCarBtn" value="" type="button">
      </div>
      <div class="questionCircle">
        <input class="questionCircleBtn" value="" type="button">
      </div>
      <div class="login">
        <input class="loginBtn" value="" type="button">
      </div>
      <div class="registered">
        <input class="registeredBtn" value="" type="button">
      </div>
    </div>
  </div>
</template>

<script>
export default {
}
</script>

<style scoped>
#header{
  width: 100%;
  height: 50px;
}
#header .logo{
  width: 100px;
  height: 15px;
  float: left;
  margin: 16px 30px 12px 136px;
}
#header .search{
  width: 199px;
  height: 24px;
  float: left;
  margin: 12px 0px 12px 0px;
}
#header .search form{
  height: 24px;
  border: none;
}
#header .search .searchButton{
  width: 24px;
  height: 24px;
  border: none;
  float: left;
  background: url("./assets/images/search.png") no-repeat left center;
  border: none;
}
#header .search .text{
  width: 165px;
  height: 24px;
  border: none;
  float: left;
  padding-left: 10px;
  font-size: 16px;
  color: #a3afbe;
}
#header .flexRight{
  width: 306px;
  height: 32px;
  float: right;
  margin: 8px 136px 6px 0px;
}
#header .teach{
  width: 64px;
  height: 18px;
  float: left;
  margin: 6px 16px 6px 0px;
}
#header .teach a{
  font-size: 16px;
  color: #595959;
  text-decoration:none;
}
#header .shoppingCar{
  width: 18px;
  height: 16px;
  float: left;
  margin: 8px 16px 8px 0px;
  border: none;
}
#header .shoppingCar .shoppingCarBtn{
  width: 16px;
  height: 16px;
  border: none;
  background: url("./assets/images/shoppingCar.png") no-repeat left center;
}
#header .questionCircle{
  width: 16px;
  height: 16px;
  float: left;
  margin: 8px 16px 8px 0px;
}
#header .questionCircle .questionCircleBtn{
  width: 16px;
  height: 16px;
  border: none;
  background: url("./assets/images/questionCircle.png") no-repeat left center;
}
#header .login{
  width: 64px;
  height: 32px;
  float: left;
  margin-right: 16px;
}
#header .login .loginBtn{
  width: 64px;
  height: 32px;
  border: none;
  background: url("./assets/images/loginBtn.png") no-repeat left center;
}
#header .registered{
  width: 64px;
  height: 32px;
  float: left;
}
#header .registered .registeredBtn{
  width: 64px;
  height: 32px;
  border: none;
  background: url("./assets/images/registeredBtn.png") no-repeat left center;
}
</style>
