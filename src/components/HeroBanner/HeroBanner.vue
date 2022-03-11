<template>
  <div class="intro">
      <!-- information and call to action -->
      <div class="info-cta">
          <div class="info">
            <p class="info-small">PREMIUM QUALITY PRODUCTS</p>
            <p class="info-big">
                SHOP TOP MENS AND WOMENS FASHION PRODUCTS ONLINE
            </p>
          </div>

          <div class="cta">
            <a href="#" class="learn-m">LEARN MORE</a>
            <a href="#" class="signup">SIGNUP FOR EXCLUSIVE OFFERS AND DISCOUNTS</a>
          </div>
      </div>
      <div class="watch">
          <div class="circle">
            <span class="quality">Top & Premium Quality Products</span>
          </div>
          <img src="../../assets/images/luxwatch.jpg" alt="" class="lux-watch">
      </div>
      <div class="navigatio">
           <ul class="navigation-item">
              <li class="pl-5"><a href="#">ABOUT US</a></li>
              <li class="pl-5"><a href="#">OUR RECENT WORK</a></li>
              <li class="pl-5"><a href="#">VISIT LOCATION</a></li>
              <li class="pl-5"><a href="#">VIEW OUR WORK</a></li>
              <li class="pl-5"><a href="#">CONTACT</a></li>
          </ul>
          <img src="../../assets/images/girl.jpg" alt="" class="girl w-52">
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
@import url('https://fonts.googleapis.com/css2?family=Montserrat:wght@500&display=swap');

.intro{
    display: flex;
    align-items: center;
}

.info-cta .info .info-big, .cta{
    width: 30rem;
}


.info-cta .info{
    display: flex;
    flex-direction: column;
    align-items: start;
}

.info{
    font-family: 'Montserrat', sans-serif;
    place-items: center;
     word-spacing: 6px;
}


.cta{
    display: flex;
}

.lux-watch{
    width: 20rem;
}
.cta .learn-m,.cta .signup{
    display: flex;
    justify-content: center;
    align-items: center;
    padding: 1.1rem 1.9rem;
    margin-right: 6px;
    text-decoration: none;
    word-spacing: 6px;
}

.cta .signup{
    background: #fff;
    color: #1c1917;
    border: 1px solid #fff;
    width: 15rem;
}
.cta .learn-m{
    background: #1c1917;
    color: #fff;
    border: 1px solid #1c1917;
    width: 8rem;
}

.info-cta .info .info-small{
    margin: 0;
}


.watch{
    padding-top: 5rem;
}
.watch .circle{
    position: relative;
    width: 150px;
    height: 150px;
    border-radius: 50%;
    background: #000;
    color: #ffff;
    display: flex;
}

.info-cta .info .info-big{
    font-size: 3rem;
}

.girl{
    width: 10rem;
}
</style>