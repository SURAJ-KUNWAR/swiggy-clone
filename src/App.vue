<template>
<the-header></the-header>
<cuisine-carousel></cuisine-carousel>
<resturant-carousel></resturant-carousel>
</template>


<script>
import CuisineCarousel from "./component/CuisineCarousel.vue"
import ResturantCarousel from "./component/ResturantCarousel.vue";
export default{
  components :{
    CuisineCarousel,
    ResturantCarousel
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