<template>
  <div class="bg-black">
    <div class="container padding-y-100">
      <div class="row">
        <div class="col-lg-6 col-md-12 col-sm-12 mt-5">
          <img src="../assets/Bicycle.png" style="width: 100%" />
        </div>
        <div class="col-lg-6 col-md-12 col-sm-12 padding-x-50 mb-5">
            <h1 class="padding-x-50 color-text-white fw-semibold">ติดต่อเรา</h1>
          <form class="padding-50">
            <div class="form-group">
              <input
                type="text"
                class="form-control-contact"
                id="formGroupExampleInput"
                placeholder="ชื่อ - นามสกุล"
              />
            </div>
            <div class="form-group">
              <input
                type="text"
                class="form-control-contact"
                id="formGroupExampleInput2"
                placeholder="เบอร์ติดต่อ"
              />
            </div>
            <div class="form-group">
              <input
                type="text"
                class="form-control-contact"
                id="formGroupExampleInput3"
                placeholder="อีเมล"
              />
            </div>
            <div class="form-group">
              <input type="date" id="birthday" class="form-control-contact" name="birthday"  placeholder="วันที่">
            </div>
            <p class="color-text-white mt-4">Lorem Ipsum is simply dummy text <br>Lorem Ipsum is simply dummy text</p>

            <button class="button-contact fw-semibold">Lorem</button>
          </form>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
.color-text-white{
    color: #ffffff;
}
.padding-y-100 {
  padding-top: 100px;
  padding-bottom: 100px;
}
.form-control-contact {
  display: block;
  width: 100%;
  padding: 0.775rem 0;
  font-size: 1rem;
  font-weight: 400;
  line-height: 1.5;
  border: none;
  background-color: rgb(0, 0, 0);
  border-bottom: 1px solid #ffffff;
  color: #ffffff;
}
.form-control-contact::placeholder {
  color: #ffffff;
}
.form-control-contact[type="date"] {
  color: #ffffff;
  background-color: transparent; 
  border: none; 
  border-bottom: 1px solid #ffffff;
}
.form-control-contact[type="date"]::placeholder {
  color: #ffffff; 
}
.form-control-contact[type="date"]::-webkit-calendar-picker-indicator,
.form-control-contact[type="date"]::-webkit-inner-spin-button {
  filter: invert(1); 
}
.padding-x-50 {
  padding-left: 50px;
  padding-right: 50px;
}
.padding-50 {
  padding: 50px;
}
.button-contact {
  background: linear-gradient(180deg, #DEE34B 0%, #D9EF0C 35.94%, #87A30D 100%);
  border-radius: 50px;
  color: black;
  border:none;
  padding: 15px 50px;
  text-align: center;
  display: inline-block;
  font-size: 16px;
  margin-top: 40px;
  cursor: pointer;
  width: 70%;
  text-transform: uppercase;
}
@import url("https://fonts.googleapis.com/css2?family=Montserrat:wght@400;500;600&display=swap");
    * {
      font-family: "Montserrat", sans-serif;
    }
</style>
