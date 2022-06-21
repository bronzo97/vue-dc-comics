<template>
  <div>
    <MyNavbar></MyNavbar>
    <div class="content-here">--> Content here &lt;-- </div>
    <div class="blue-section">
        <div class="card">
          <img src="./assets/img/buy-comics-digital-comics.png" alt="">
          <div></div>
        </div>
        <div class="card">
          <img src="./assets/img/buy-comics-merchandise.png" alt="">
          <div></div>
        </div>
        <div class="card">
          <img src="./assets/img/buy-comics-subscriptions.png" alt="">
          <div></div>
        </div>
        <div class="card">
          <img src="./assets/img/buy-comics-shop-locator.png" alt="">
          <div></div>
        </div>
        <div class="card">
          <img src="./assets/img/buy-dc-power-visa.svg" alt="">
          <div></div>
        </div>
    </div>
    <BannerSignUp></BannerSignUp>
    <MyFooter></MyFooter>
  </div>
</template>

<script>

import MyNavbar from './components/MyNavbar.vue';
import MyFooter from './components/MyFooter.vue';
import BannerSignUp from './components/BannerSignUp.vue';

export default {
  name: 'App',
  components: {
    MyNavbar,
    MyFooter,
    BannerSignUp
  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

.content-here {
  background-color: #1C1C1C;
  color: #fff;
  height: 120px;
  display: flex;
  align-items: center;
}

.blue-section {
  background-color: #1E82F6;
  // height: 150px;
  display: flex;
  justify-content: space-around;
  align-items: center;
}

.blue-section img {
  width: 30%;
  height: 30%;
  display: flex;
}


</style>
