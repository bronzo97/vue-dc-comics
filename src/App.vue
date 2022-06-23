<template>
  <div>
    <MyNavbar></MyNavbar>
    <ProductsList></ProductsList>
    <div class="blue-section">
        <div class="my-card" v-for="(imgage, i) in dcCards" :key="i">
          <img :src="imgage.img" alt="">
          <div>{{imgage.description}}</div>
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
import ProductsList from './components/ProductsList.vue';

export default {
  name: 'App',
  components: {
    MyNavbar,
    MyFooter,
    BannerSignUp,
    ProductsList,
},
  data() {
    return {
      dcCards: [
        {
          img: require('./assets/img/buy-comics-digital-comics.png'),
          description: 'DIGITAL COMICS',
        },
        {
          img: require('./assets/img/buy-comics-merchandise.png'),
          description: 'DC MERCHANDISE',

        },
        {
          img: require('./assets/img/buy-comics-subscriptions.png'),
          description: 'SUBSCRIPTION',

        },
        {
          img: require('./assets/img/buy-comics-shop-locator.png'),
          description: 'COMIC SHOP LOCATOR',

        },
        {
          img: require('./assets/img/buy-dc-power-visa.svg'),
          description: 'DC POWER VISA',
        },
      ]
    }
  }
}
</script>

<style lang="scss">

	@import "assets/scss/main.scss";

</style>
