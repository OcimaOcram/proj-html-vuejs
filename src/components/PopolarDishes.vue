<template>
   <div class="container">
   
   <div class="absolute-container">
        <ul>
            <li><b> 24/7 Delivery</b></li>
            <li><b>Over 1000 Dishes</b></li>
            <li><b>In App Order</b></li>
            <li><b>Fast Delivery</b></li>
        </ul>

    </div>
    
    
    
    <h1>
        Our Most Popolar Dishes
    </h1>
    <PopolarDishesCard/>


    <div class="button">
        <b>Start Your Order</b>
    </div>


    <div class="wave">
        <!-- <svg viewBox="0 0 500 500" preserveAspectRatio="xMinYMin meet">
            <path d="M0,100 C150,100 350,0 50,100 L500,00 L0,0 Z" style="stroke: none; fill: white;"></path>
        </svg> -->
    </div>



   </div>
</template>

<script>
import PopolarDishesCard from './PopolarDishesCard.vue';


export default {
    components: { PopolarDishesCard }
}
</script>


<style scoped lang="scss">
.container {
    text-align: center;
    color: black;
    position: relative;
}
h1 {
    margin-top: 150px;
}
.absolute-container {
    position: absolute;
    top: -150px;
    left: 50%;
    transform: translate(-50%, -50%);
}
ul {
    
    
    background-color: white;
}

li {
    list-style-type: none;
    padding:30px;
    display: inline-block;
    
}
.button {
    background-color: red;
    color: white;
    display: inline-block;
    padding: 10px;
    border-radius: 50px;

}
svg {
  display: inline-block;
//   position: absolute;
  top: 0;
  left: 0;
  background-color: rgba(0, 255, 255, 0);
}
.wave {
  display: inline-block;
  position: relative;
  width: 100%;
  margin-top: 10%;
  padding-bottom: 40%;
  vertical-align: middle;  
  background-image: url(../assets/img/first-order-background-scaled.jpg);
  background-repeat: no-repeat;
  background-size: contain;
}

</style>