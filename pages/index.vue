<template>
  <div>
    <div class="banner-section-bg">
      <v-container>
        <v-row>
          <v-col cols="12" sm="8" md="6">
            <div class="banner-content">
              <h1>Welcome Remi</h1>
              <v-btn
                color="white"
                class="ma-2 white--dark theme-btn">
                Change personal details
                <v-icon right class="btn-icon-style">
                  mdi-cloud-upload
                </v-icon>
              </v-btn>
            </div>
          </v-col>

        </v-row>
      </v-container>
      <v-row>
        <v-col cols="12">
          <img src="../assets/banner.png" alt="" class="banner-img">
        </v-col>
      </v-row>
    </div>

    <SingleProduct/>
    <hr>
    <SingleProductTwo/>
  </div>
</template>
<style scoped>
.theme-btn {
  padding: 25px 20px !important;
  border: 1px solid #d0d0d0 !important;
  box-shadow: none !important;
  font-size: 12px !important;
  background-color: #fff !important;
  border-radius: 0px !important;
}

.btn-icon-style {
  margin-left: 20px !important;
}

.banner-content {
  padding-top: 100px;

}

.banner-content h1 {
  font-weight: 300;
  margin-left: 6px;
  margin-bottom: 10px;
}

.banner-section-bg {
  background-color: #fafafa;
  /*background-color: #d0d0d0;*/
  /*display: flex;*/
  /*align-items: center;*/
  /*background-image: url(./assets/banner.png);*/
  /*object-position: bottom;*/
  /*object-fit: scale-down;*/
}

.banner-section-bg img {
  height: 150px;
  padding-top: 20px;
  margin-bottom: 10px;
  width: 100%;
}
</style>
<script>
import SingleProduct from "../components/SingleProduct";
import SingleProductTwo from "../components/SingleProductTwo";

export default {
  components: {SingleProduct, SingleProductTwo}
}
</script>
