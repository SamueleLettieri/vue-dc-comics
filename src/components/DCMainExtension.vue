<template>
  <div class="ms_background-blue p-5">
    <div class="container">
        <div class="d-flex justify-content-center">
            <div class="mx-4 ms_font"><a class="ms_link" href="#"><img class="me-1 ms_img" src="../assets/img/buy-comics-digital-comics.png" alt="">DIGITAL COMICS</a></div>
            <div class="mx-4 ms_font"><a class="ms_link" href="#"><img class="me-1 ms_img" src="../assets/img/buy-comics-merchandise.png" alt="">DC MERCHANDISE</a></div>
            <div class="mx-4 ms_font"><a class="ms_link" href="#"><img class="me-1 ms_img" src="../assets/img/buy-comics-subscriptions.png" alt="">SUBSCRIPTION</a></div>
            <div class="mx-4 ms_font"><a class="ms_link" href="#"><img class="me-1 ms_img-locator" src="../assets/img/buy-comics-shop-locator.png" alt="">COMIC SHOP LOCATOR</a></div>
            <div class="ms-4 ms_font"><a class="ms_link" href="#"><img class="me-1 ms_img-locator" src="../assets/img/buy-dc-power-visa.svg" alt="">DC POWER VISA</a></div>
        </div>
    </div>
  </div>
</template>

<script>
export default {

}
</script>




<style lang="scss" scoped>
@import "../styles/variables.scss";


.ms_background-blue{
    background-color: $colorplus;
}

.ms_font{
    font-size: 12px;
}

.ms_img{
    width: 25%
}

.ms_img-locator{
    width: 17%;
}

.ms_link{
    color: $colorHeader;
    text-decoration: none;
}

</style>