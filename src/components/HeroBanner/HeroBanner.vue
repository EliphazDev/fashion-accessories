<template>
  <div class="intro">
      <!-- information and call to action -->
      <div class="info-cta">
          <p>PREMIUM QUALITY PRODUCTS</p>
          <p>
              SHOP TOP MENS AND WOMENS FASHION PRODUCTS ONLINE
          </p>
          <button>LEARN MORE</button>
          <button>SIGNUP FOR EXCLUSIVE OFFERS AND DISCOUNTS</button>
      </div>
      <div class="watch">
          <span>Top & Premium Quality Products</span>
          <img src="../../assets/images/luxwatch.jpg" alt="" class="lux-watch">
      </div>
      <div class="navigatio">
          <NavigationBar />
          <img src="../../assets/images/girl.jpg" alt="" class="girl">
      </div>

      <div class="services">
          <div class="small-list">
            <span>133 WATCHES</span>
            <span>94 SUNGLASSES</span>
            <span>80 BRACHELETTES</span>
            <span>50 RINGS</span>
          </div>
          <img src="../../assets/images/glass.jpg" alt="" class="glass">
      </div>
  </div>
</template>

<script>
import NavigationBar from '../NavigationBar/NavigationBar.vue'

export default {
    name: 'HeroBanner',
    components: {
        NavigationBar
    }
}
</script>

<style>

</style>