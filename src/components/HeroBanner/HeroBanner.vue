<template>
  <div class="intro">
      <!-- information and call to action -->
      <div class="info-cta">
          <div class="info text-3xl">
              <p>PREMIUM QUALITY PRODUCTS</p>
          <p>
              SHOP TOP MENS AND WOMENS FASHION PRODUCTS ONLINE
          </p>
          </div>

          <div class="cta">
            <a href="#" class="learn-m">LEARN MORE</a>
            <a href="#" class="signup">SIGNUP FOR EXCLUSIVE OFFERS AND DISCOUNTS</a>
          </div>
      </div>
      <div class="watch">
          <span class="quality">Top & Premium Quality Products</span>
          <img src="../../assets/images/luxwatch.jpg" alt="" class="lux-watch">
      </div>
      <div class="navigatio">
          <!-- <NavigationBar /> -->
          <!-- <img src="../../assets/images/girl.jpg" alt="" class="girl w-52"> -->
      </div>

      <!-- <div class="services">
          <div class="small-list">
            <span>133 WATCHES</span>
            <span>94 SUNGLASSES</span>
            <span>80 BRACHELETTES</span>
            <span>50 RINGS</span>
          </div>
          <img src="../../assets/images/glass.jpg" alt="" class="glass">
      </div> -->
  </div>
</template>

<script>
// import NavigationBar from '../NavigationBar/NavigationBar.vue'

export default {
    name: 'HeroBanner',
    components: {
        // NavigationBar
    }
}
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Open+Sans:wght@300&display=swap');
.info{
    font-family: 'Open Sans', sans-serif;
}
.intro{
    display: flex;
    justify-content: start;
    align-items: center;
}
.lux-watch{
    width: 20rem;
}
.cta .learn-m, .cta .signup{
    background: #1c1917;
    color: #ffff;
    padding: 13px 23px;
    font-weight: bold;
    margin-right: 6px;
    text-decoration: none;
}

.cta{
    display: flex;
}

.watch{
    padding-top: 5rem;
}
.watch .quality{
    position: relative;
    bottom: 28rem;
    left: 10rem;
}

.info-cta .info{
    font-size: 24px;
}
</style>