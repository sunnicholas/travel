<template>
  <div>
    <home-header></home-header>
    <home-swiper></home-swiper>
<!--    <hello-world></hello-world>-->
  </div>
</template>

<script>
import HomeHeader from './components/Header'
import HomeSwiper from './components/Swiper'
import HelloWorld from './components/HelloWorld'
export default {
  name: 'Home',
  components: {
    HomeSwiper,
    HomeHeader,
    HelloWorld
  }
}
</script>

<style>

</style>
