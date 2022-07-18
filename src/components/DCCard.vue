<template>
  <div class="ms_margin">
    <a href="#">
        <div><img class="ms_img" :src="product.thumb" :alt="product.series"></div>
        <h5 class="ms_titolo">{{product.series}}</h5>
    </a>
  </div>
</template>

<script>
export default {
    props:{
        "product": {
            type: Object,
            require: true,
        }
    }
}
</script>

<style lang="scss" scoped>
 
.ms_margin{
   width: calc((100% / 6) - 30px);
  margin: 0 15px;
  margin-bottom: 60px;
}

a{
    text-decoration: none;
}
.ms_img{
  object-fit: cover;
  object-position: top;
  width: 190px;
  height: 180px;
}

.ms_titolo{
  color: white;
  padding-top: 20px;
}

</style>