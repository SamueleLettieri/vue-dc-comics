<template>
  <footer class="p-5">
    <div class="container">
        <div class="d-flex justify-content-between">
            <div class="p-2 ms_border-button"><a class="ms_link" href="#">SIGN-UP NOW!</a></div>
            <div>
                <h3>
                    <span class="ms_color me-3">FOLLOW US </span>
                    <a class="ms-3" href="#"><img src="../assets/img/footer-facebook.png" alt=""></a>
                    <a class="ms-3" href="#"><img src="../assets/img/footer-twitter.png" alt=""></a>
                    <a class="ms-3" href="#"><img src="../assets/img/footer-youtube.png" alt=""></a>
                    <a class="ms-3" href="#"><img src="../assets/img/footer-pinterest.png" alt=""></a>
                    <a class="ms-3" href="#"><img src="../assets/img/footer-periscope.png" alt=""></a>
                </h3>
            </div>
        </div>
    </div>
  </footer>
</template>




<script>
export default {

}
</script>




<style lang="scss" scoped>
@import "../styles/variables.scss";


footer{
    background-color: $colorfooter;
}

.ms_border-button{
    border: 2px solid $colorplus;
}
.ms_link{
    color: $colorHeader;
    text-decoration: none;
}

.ms_color{
    color:$colorplus;
}

</style>