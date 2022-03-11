<template>
  <div class="navigation">
      <nav>
          <div class="brand-logo">
              LOGO
          </div>
          <ul class="navigation-item">
              <li class="pl-5"><a href="#">ABOUT US</a></li>
              <li class="pl-5"><a href="#">OUR RECENT WORK</a></li>
              <li class="pl-5"><a href="#">VISIT LOCATION</a></li>
              <li class="pl-5"><a href="#">VIEW OUR WORK</a></li>
              <li class="pl-5"><a href="#">CONTACT</a></li>
          </ul>
      </nav>
  </div>
</template>

<script>
export default {
    name: 'NavigationBar'
}
</script>

<style>

@import url('https://fonts.googleapis.com/css2?family=Roboto+Serif:wght@400&display=swap');

.navigation{
  font-family: 'Roboto Serif', sans-serif;
}

.navigation nav{
    display: flex;
    justify-content: space-between;
    align-items: center;
}
nav ul {
    display: flex;
}
ul li{
    list-style: none;
    padding-left: 16px;
}
li a{
    text-decoration: none;
    color: #000;

}
</style>