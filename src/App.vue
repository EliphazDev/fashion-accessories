<template>
  <NavigationBar />
  <HeroBanner />
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
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
