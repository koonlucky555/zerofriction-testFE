<template>
  <div class="bg-green">
    <div class="container padding-y-100">
      <h1 class="text-uppercase text-60 text-center">Lorem Ipsum</h1>
      <div class="row mt-5">
        <div
          class="col-lg-4 col-md-6 col-sm-12"
          v-for="product in products"
          :key="product.id"
        >
          <div class="card">
            <img
              class="card-img-top"
              :src="product.thumbnail"
              alt="Card image cap"
            />
            <div class="card-body">
              <h5 class="card-title fw-bold">
                {{ product.title
                }}<span class="badge text-bg-danger ml-25"
                  >Discount : {{ product.discountPercentage }} %</span
                >
              </h5>
              <p class="card-text">{{ product.description }}</p>
              <p class="card-text fw-semibold">
                Brand: <span class="fw-normal">{{ product.brand }}</span>
              </p>
              <p class="card-text fw-semibold">
                Category: <span class="fw-normal">{{ product.category }}</span>
              </p>
              <p class="card-text fw-semibold">
                Price : <span class="fw-normal">{{ product.price }}</span>
              </p>
              <p class="card-text fw-semibold">
                Rating: <span class="fw-normal">{{ product.rating }}</span>
              </p>
              <p class="card-text fw-semibold">
                Stock: <span class="fw-normal">{{ product.stock }}</span>
              </p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
 @import url("https://fonts.googleapis.com/css2?family=Montserrat:wght@400;500;600&display=swap");
    * {
      font-family: "Montserrat", sans-serif;
    }
.card-img-top {
  width: 100%;
  height: 250px;
  object-fit: cover;
}
.color-title-green {
  color: #d9ef0c;
}
.color-title-white {
  color: #ffffff;
}
.padding-y-100 {
  padding-top: 100px;
  padding-bottom: 100px;
}

.text-60 {
  font-size: 60px;
}

.bg-green {
  background-color: #d9ef0c;
}
.ml-25 {
  margin-left: 25px;
}
</style>

<script>
import axios from "axios";
export default {
  data() {
  return {
    products: [],
    urlProduct: "https://dummyjson.com/products?limit=3",
  };
},
  created() {
    this.fetchProduct();
  },
  methods: {
    fetchProduct() {
  axios
    .get(this.urlProduct)
    .then((res) => {
      this.products = res.data.products; 
      console.log(this.products);
    })
    .catch((err) => {
      console.error(err);
    });
},
  },
};
</script>
