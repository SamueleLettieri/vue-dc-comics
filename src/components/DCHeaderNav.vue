<template>
  <header>
        <div class="container">
            <div class="d-flex justify-content-between ">
                <div class=""><img src="../assets/img/dc-logo.png" alt=""></div>
                <div>
                    <ul>
                        <li><a href="#">CHARACTERS</a></li>
                        <li class="active"><a class="ms_activ-link" href="#">COMICS</a></li>
                        <li><a href="#">MOVIES</a></li>
                        <li><a href="#">TV</a></li>
                        <li><a href="#">GAMES</a></li>
                        <li><a href="#">COLLECTIBLES</a></li>
                        <li><a href="#">VIDEOS</a></li>
                        <li><a href="#">FANS</a></li>
                        <li><a href="#">NEWS</a></li>
                        <li><a href="#">SHOP</a></li>
                    </ul>
                </div>
            </div>
        </div>    
  </header>
</template>

<script>
export default {

}
</script >


<style lang="scss" scoped>
@import "../styles/variables.scss";

header{
  background-color: $colorHeader;
}

.ms_wisth{
  height: 10px;
}

img{
  width: 80%;
  padding: 10px 0px 15px 0px;
}

ul{
margin: 0;
}

li{
  display: inline-block;
  padding: 39px 0px 49px 0px;
  margin-left: 10px;
  line-height: normal;
  font-size: 12px;
}

.active{
  border-bottom:4px solid $colorplus;
  line-height: normal;
}

.ms_activ-link{
    color: $colorplus;
}

a{
  text-decoration: none;
  color: black;
}
</style>