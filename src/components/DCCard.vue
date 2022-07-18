<template>
  <div class="ms_margin">
    <div><img class="ms_img" :src="imageUrl" alt="title"></div>
    <h5 class="ms_titolo">{{title}}</h5>
  </div>
</template>

<script>
export default {
    props:{
        "imageUrl": string,
        "title": string,
    }
}
</script>

<style lang="scss">

.ms_margin{
  margin: 0 13px;
  margin-bottom: 60px;
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