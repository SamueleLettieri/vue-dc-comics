<template>
  <main class="">
    <div class="container">
        <div class="d-flex justify-content-between">
            <div class="w-50 p-5">
                <div class="ms_d-flex-collum">
                    <h3 class="me-5">DC COMICS</h3>
                    <ul>
                        <li class="me-4"><a href="#">Characters</a></li>
                        <li class="me-4"><a href="#">Comics</a></li>
                        <li class="me-4"><a href="#">Movies</a></li>
                        <li class="me-4"><a href="#">TV</a></li>
                        <li class="me-4"><a href="#">Games</a></li>
                        <li class="me-4"><a href="#">Videos</a></li>
                        <li class="me-4"><a href="#">News</a></li>
                    </ul>
                    <h3 class="me-5">SHOP</h3>
                    <ul>
                        <li class="me-4"><a href="#">Shop DC</a></li>
                        <li class="me-4"><a href="#">Shop DC Collection</a></li>
                    </ul>
                    <h3 class="me-5">DC</h3>
                    <ul>
                        <li class="me-4"><a href="#">Terms Of Use</a></li>
                        <li class="me-4"><a href="#">Privacy Policy (New)</a></li>
                        <li class="me-4"><a href="#">Ad Choices</a></li>
                        <li class="me-4"><a href="#">Advertising</a></li>
                        <li class="me-4"><a href="#">Jobs</a></li>
                        <li class="me-4"><a href="#">Subscriptions</a></li>
                        <li class="me-4"><a href="#">Talent Workshops</a></li>
                        <li class="me-4"><a href="#">CPSC Certificates</a></li>
                        <li class="me-4"><a href="#">Raitings</a></li>
                        <li class="me-4"><a href="#">Shop Help</a></li>
                        <li class="me-4"><a href="#">Contact Us</a></li>
                    </ul>
                    <h3 class="me-5">SITES</h3>
                    <ul>
                        <li class="me-4"><a href="#">DC</a></li>
                        <li class="me-4"><a href="#">MAD Magazine</a></li>
                        <li class="me-4"><a href="#">DC Kids</a></li>
                        <li class="me-4"><a href="#">DC Universe</a></li>
                        <li class="me-4"><a href="#">DC Power Visa</a></li>
                    </ul>    
                </div>
            </div>
            <div class="ms_img-Dc-box"><img class="ms_img-Dc" src="../assets/img/dc-logo-bg.png" alt=""></div>
        </div>
    </div>
  </main>
</template>

<script>
export default {

}
</script>



<style lang="scss" scoped>
main{
    background-image: url(../assets/img/footer-bg.jpg);
    height: 400px;
}

h3{
    color: white;
    font-size: 20px;
    padding-bottom: 2px;
}

.ms_d-flex-collum{ 
    width: 55%; 
    height: 345px;
    display: flex;
    flex-direction: column;
    flex-wrap: wrap;
}

ul{
    padding-left: 0;
}


a{
  text-decoration: none;
  color: rgb(158, 156, 156);
  font-size: 12px;
}

.ms_img-Dc-box{
    height: 400px;
    width: 37%;
}
.ms_img-Dc{
    width: 510px;
    object-fit: cover;
    height: 100%;
}
</style>