<template>
  <div>
    <div class="ms_background-img">
    </div>  
    <div class="ms_background-color p-4">
      <div class="container">
        <h3>CURRENT SERIES</h3>
        <div class="ms_box">
          <div class="ms_margin">
            <div><img class="ms_img" src="https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/AC1000_DLX_162-001_HD_5ba13723281ab0.37845353.jpg?itok=ZsI-C5eX" alt=""></div>
            <h5 class="ms_titolo">ACTION COMICS</h5>
          </div>
          <div class="ms_margin">
            <div><img class="ms_img" src="https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/AC1000_DLX_162-001_HD_5ba13723281ab0.37845353.jpg?itok=ZsI-C5eX" alt=""></div>
            <h5 class="ms_titolo">ACTION COMICS</h5>
          </div>
          <div class="ms_margin">
            <div><img class="ms_img" src="https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/AC1000_DLX_162-001_HD_5ba13723281ab0.37845353.jpg?itok=ZsI-C5eX" alt=""></div>
            <h5 class="ms_titolo">ACTION COMICS</h5>
          </div>
          <div class="ms_margin">
            <div><img class="ms_img" src="https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/AC1000_DLX_162-001_HD_5ba13723281ab0.37845353.jpg?itok=ZsI-C5eX" alt=""></div>
            <h5 class="ms_titolo">ACTION COMICS</h5>
          </div>
          <div class="ms_margin">
            <div><img class="ms_img" src="https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/AC1000_DLX_162-001_HD_5ba13723281ab0.37845353.jpg?itok=ZsI-C5eX" alt=""></div>
            <h5 class="ms_titolo">ACTION COMICS</h5>
          </div>
          <div class="ms_margin">
            <div><img class="ms_img" src="https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/AC1000_DLX_162-001_HD_5ba13723281ab0.37845353.jpg?itok=ZsI-C5eX" alt=""></div>
            <h5 class="ms_titolo">ACTION COMICS</h5>
          </div>
          <div class="ms_margin">
            <div><img class="ms_img" src="https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/AC1000_DLX_162-001_HD_5ba13723281ab0.37845353.jpg?itok=ZsI-C5eX" alt=""></div>
            <h5 class="ms_titolo">ACTION COMICS</h5>
          </div>
        </div>
        <div></div>
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

.ms_background-img{
    background-image: url(../assets/img/jumbotron.jpg);
    background-repeat: no-repeat;
    height: 400px;
    width: 100%;
}

.ms_background-color{
  background-color: rgb(41, 41, 41);
}

h3{
  color: white;
  background-color: $colorplus;
  display: inline-block;
  padding: 7px 25px;
  position: relative;
  bottom: 45px;
}

.ms_box{
  width: 100%;
  display: flex;
  flex-wrap: wrap;
}

.ms_margin{
  margin: 0 10px;
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