<template>
    <div id="myCarousel" class="carousel slide  bg-black" data-ride="carousel">
      <div class="carousel-inner">

        <div class="carousel-item active bg-black">
          <div class="container padding-y-100" style="max-width: 800px;">
            <div class="col-lg-12">
              <h1 class="text-uppercase text-60 text-center color-title-white">Lorem Ipsum <span class="color-title-green">Lorem</span></h1>
            </div>
            <div class="col-lg-12 d-flex justify-content-center my-5">
              <img src="../assets/user-section2.png" class="img-fluid" alt="User Section 2">
            </div>
            <div class="col-lg-12 my-5">
              <p class="text-26 text-center color-title-white">Lorem Ipsum is simply</p>
              <p class="text-18 text-center color-title-white">Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book.</p>
            </div>
          </div>
        </div>

        <div class="carousel-item bg-black">
          <div class="container padding-y-100" style="max-width: 800px;">
            <div class="col-lg-12">
              <h1 class="text-uppercase text-60 text-center color-title-white">Lorem Ipsum <span class="color-title-green">Lorem</span></h1>
            </div>
            <div class="col-lg-12 d-flex justify-content-center my-5">
              <img src="../assets/user-section2.png" class="img-fluid" alt="User Section 2">
            </div>
            <div class="col-lg-12 my-5">
              <p class="text-26 text-center color-title-white">Lorem Ipsum is simply</p>
              <p class="text-18 text-center color-title-white">Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book.</p>
            </div>
          </div>
        </div>

        <div class="carousel-item bg-black">
          <div class="container padding-y-100" style="max-width: 800px;">
            <div class="col-lg-12">
              <h1 class="text-uppercase text-60 text-center color-title-white">Lorem Ipsum <span class="color-title-green">Lorem</span></h1>
            </div>
            <div class="col-lg-12 d-flex justify-content-center my-5">
              <img src="../assets/user-section2.png" class="img-fluid" alt="User Section 2">
            </div>
            <div class="col-lg-12 my-5">
              <p class="text-26 text-center color-title-white">Lorem Ipsum is simply</p>
              <p class="text-18 text-center color-title-white">Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book.</p>
            </div>
          </div>
        </div>
      </div>
  
     
      <a class="carousel-control-prev" href="#myCarousel" data-slide="prev">
        <span class="carousel-control-prev-icon"></span>
      </a>
      <a class="carousel-control-next" href="#myCarousel" data-slide="next">
        <span class="carousel-control-next-icon"></span>
      </a>
      
    </div>
  </template>
  
  <script>
    $(document).ready(function () {
      $("#myCarousel").carousel();
    });
  </script>
  

<style scoped>
 @import url("https://fonts.googleapis.com/css2?family=Montserrat:wght@400;500;600&display=swap");
    * {
      font-family: "Montserrat", sans-serif;
    }
.text-60{
    font-size: 60px;
}
.color-title-green{
    color: #D9EF0C;
}

.color-title-white{
    color: #ffffff;
}
.padding-y-100{
    padding-top: 100px;
    padding-bottom: 100px;
}
.text-26{
    font-size: 26px;
}
.text-18{
    font-size: 18px;
}
.carousel-item {
    color: #fff;
    background-color: #000;
  }
</style>