<script setup>
import { ref } from "vue";

defineProps({
  msg: String,
});

const count = ref(0);
</script>
<template>
  <div class="bg-black">
    <div class="container">
      <nav class="navbar navbar-expand-lg bg-black">
        <div class="container-fluid">
          <img src="../assets/logo.png" class="img-logo-size" />
          <a class="nav-brand-custom ms-3 text-uppercase color-title-white fst-italic fw-semibold text-green-shadow" href="#">
            Lorem <span style="color: #D9EF0C;">Ipsum</span>
          </a>
          <button
            class="navbar-toggler"
            type="button"
            data-bs-toggle="collapse"
            data-bs-target="#navbarSupportedContent"
            aria-controls="navbarSupportedContent"
            aria-expanded="false"
            aria-label="Toggle navigation"
          >
            <span class="navbar-toggler-icon"></span>
          </button>
          <div class="collapse navbar-collapse ml-50" id="navbarSupportedContent">
            <ul class="navbar-nav me-auto mb-2 mb-lg-0">
              <li class="nav-item">
                <a
                  class="nav-link active text-uppercase color-title-white fw-semibold nav-text-size"
                  aria-current="page"
                  href="#"
                  >Lorem</a
                >
              </li>
              <li class="nav-item dropdown">
                <a
                  class="nav-link dropdown-toggle text-uppercase color-title-white fw-semibold nav-text-size"
                  href="#"
                  role="button"
                  data-bs-toggle="dropdown"
                  aria-expanded="false"
                >
                  Lorem
                </a>
                <ul class="dropdown-menu">
                  <li class="ml-20">
                    <a class="dropdown-item text-uppercase fw-semibold nav-dropdown-size" href="#">Lorem</a>
                  </li>
                  <li class="ml-20">
                    <a class="dropdown-item text-uppercase fw-semibold nav-dropdown-size" href="#">Lorem</a>
                  </li>
                  <li class="ml-20">
                    <a class="dropdown-item text-uppercase fw-semibold nav-dropdown-size" href="#">Lorem</a>
                  </li>
                </ul>
              </li>
              <li class="nav-item">
                <a
                  class="nav-link text-uppercase color-title-white fw-semibold nav-text-size"
                  aria-current="page"
                  href="#"
                  >LoremIpsum</a
                >
              </li>
              <li class="nav-item">
                <a
                  class="nav-link text-uppercase color-title-white fw-semibold nav-text-size"
                  aria-current="page"
                  href="#"
                  >Lorem & Ipsum</a
                >
              </li>
              <li class="nav-item">
                <a
                  class="nav-link text-uppercase color-title-white fw-semibold nav-text-size"
                  aria-current="page"
                  href="#"
                  >Lorem</a
                >
              </li>
            </ul>
          </div>
        </div>
      </nav>
    </div>
  </div>
</template>

<style scoped>
.read-the-docs {
  color: #888;
}
.color-title-white {
  color: #ffffff;
}
.ml-50 {
  margin-left: 150px;
}
.ml-20 {
  margin-left: 20px;
}
.img-logo-size {
  width: 55px;
  height: 60px;
}
.navbar-nav .nav-item .nav-link.active,
.navbar-nav .nav-item .nav-link:hover {
  color: #D9EF0C; 
}
.navbar-nav .nav-link.active, .navbar-nav .nav-link.show {
  color: #ffffff; 
}
.nav-brand-custom{
  text-decoration: none;
  font-size: 24px;
}
.nav-text-size{
  font-size: 18px;
}
.nav-dropdown-size{
  font-size: 16px;
}
.text-green-shadow{
    text-shadow: 0px 4px 30px rgba(33, 97, 47, 1);
}
.navbar-toggler-icon{
  color: #ffffff;
}
</style>
