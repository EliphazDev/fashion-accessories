<template>
  <div class="container">
    <NavigationBar />
    <HeroBanner />
  </div>
</template>

<script>
import NavigationBar from './components/NavigationBar/NavigationBar.vue'
import HeroBanner from './components/HeroBanner/HeroBanner.vue'

export default {
  name: 'App',
  components: {
    NavigationBar,
    HeroBanner,
  }
}
</script>

<style>
.container{
  margin: 0 60px;
}
</style>
