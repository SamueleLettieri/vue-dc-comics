<template>
  <header>
        <div class="container">
            <div class="d-flex justify-content-between ">
                <div class="w-25"><img src="../assets/img/dc-logo.png" alt=""></div>
                <div>
                    <ul>
                        <li>
                            <a href="#">CHARACTERS</a>
                        </li>
                        <li class="active">
                            <a href="#">COMICS</a>
                        </li>
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

  img{
    height: 70%;
    padding: 10px;
  }



  li{
    display: inline-block;
    padding: 30px 0px;
    margin: 0px 10px;
    font-size: 10px;

  }
    .active{
    border-bottom:3px solid $colorplus;
    }

  a{
    text-decoration: none;
    color: black;
  }
</style>