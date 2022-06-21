<template>
  <div>
    <MyNavbar></MyNavbar>
    <div class="content-here">--> Content here &lt;-- </div>
    <div class="blue-section">
        <div class="card">
          <img src="./assets/img/buy-comics-digital-comics.png" alt="">
          <div>DIGITAL COMICS</div>
        </div>
        <div class="card">
          <img src="./assets/img/buy-comics-merchandise.png" alt="">
          <div>DC MERCHANDISE</div>
        </div>
        <div class="card">
          <img src="./assets/img/buy-comics-subscriptions.png" alt="">
          <div>SUBSCRIPTION</div>
        </div>
        <div class="card">
          <img src="./assets/img/buy-comics-shop-locator.png" alt="">
          <div>COMIC SHOP LOCATOR</div>
        </div>
        <div class="card">
          <img src="./assets/img/buy-dc-power-visa.svg" alt="">
          <div>DC POWER VISA</div>
        </div>
    </div>
    <MyFooter></MyFooter>
    <BannerSignUp></BannerSignUp>

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
  min-height: 100px;
  max-height: 150px;
  display: flex;
  justify-content: space-around;
  align-items: center;
}

.card {
  display: flex;
  height: 40px;
  align-items: center;
  color: #fff;
  
}

.blue-section img {
  height: 100%;
  display: flex;
  padding: 0.5rem;
}


</style>
