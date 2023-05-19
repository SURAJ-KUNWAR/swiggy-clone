<template>
  <div class="carousel">
    <h1 calss = carousel__heading> I am a resturant Carousel</h1>
    <div class="carousel__cards">
      <ResturantCard></ResturantCard> 
      <ResturantCard></ResturantCard>
      <ResturantCard></ResturantCard>
      <ResturantCard></ResturantCard>
    </div>
  
  </div>
  
 
</template>
<script>
import ResturantCard from "../Cards/ResturantCard";
export default{
    components:{
      ResturantCard 
    } 
}

</script>

<style scoped lang="scss">

  .carousel{
    padding: 2rem;
    border : solid 1px red;
    &.__heading {
      font-family: "Basis Grotesque Pro";
    font-size: 24px;
    font-weight: 800;
    line-height: 28px;
    letter-spacing: -0.4px;
    color: rgba(2, 6, 12, 0.92);
    overflow: hidden;
    width: 100%;
    display: -webkit-box;
    overflow-wrap: break-word;
    -webkit-line-clamp: 2;
    -webkit-box-orient: vertical;
    }

    &.__cards{
      display: flex;
    }
  }
  
  
  
  
</style>