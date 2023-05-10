<template>
  <the-header></the-header>
<cuisine-carousel></cuisine-carousel>
</template>


<script>
import CuisineCarousel from "./component/CuisineCarousel.vue"
export default{
  components :{
    CuisineCarousel
  }
}
</script>
<style>
*{
  margin: 0px;
  padding: 0px;
  box-sizing: border-box;
}
html{
  font-size: 62.5%;
}
</style>