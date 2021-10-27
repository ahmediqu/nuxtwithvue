<template>
  <section class="single-product">
    <v-container>
      <v-row class="justify-center align-center">
        <v-col cols="12" xs="12" sm="12" md="4" lg="4">
          <div>
            <img src="../assets/product.png" alt="" class="img-fluid">
          </div>
        </v-col>
        <v-col cols="12" lg="7" md="7" sm="12" xs="12">
          <div class="product-details">
            <div class="d-flex align-center">
              <h2>Shampoo</h2>
              <v-btn
                color="white"
                class="ma-2 white--dark theme-btn-sm">
                paid
              </v-btn>
              <v-btn
                color="white"
                class="ma-2 white--dark theme-btn-sm">
                delivered
              </v-btn>
            </div>
            <p>
              For personalised advice, you are welcome to arrange a video consultation with a trained consultant; or to
              use our live assistance for guidance while browsing online.
            </p>
            <div class="product-btn">
              <v-btn
                color="white"
                class="ma-2 white--dark theme-btn">

                View order details
                <v-icon right class="btn-icon-style">
                  mdi-arrow-right
                </v-icon>

              </v-btn>

              <v-btn
                color="white"
                class="ma-2 white--dark theme-btn"
              >
                View order history
                <v-icon right class="btn-icon-style">
                  mdi-book-open-outline
                </v-icon>
              </v-btn>
            </div>
          </div>
        </v-col>
      </v-row>
    </v-container>
  </section>
</template>

<script>


export default {
  name: "SingleProductTwo",

}
</script>

<style scoped>


.theme-btn {
  padding: 25px 20px !important;
  border: 1px solid #d0d0d0 !important;
  box-shadow: none !important;
  font-size: 12px !important;
  background-color: #fff !important;
  border-radius: 0px !important;
}

.theme-btn-sm {
  padding: 10px 10px !important;
  border: 1px solid #d0d0d0 !important;
  box-shadow: none !important;
  font-size: 8px !important;
  background-color: #fff !important;
  border-radius: 0px !important;
}

.product-details h2 {
  font-weight: 300;
  font-size: 25px;
  padding-right: 20px;
  margin-left: 6px;

}

.product-details p {
  font-weight: 300;
  font-size: 16px;
  line-height: 30px;
  margin-top: 15px;
  margin-left: 6px;
}

.single-product {
  background-color: #fafafa;
}

.slider {
  width: 100%;
}
</style>
