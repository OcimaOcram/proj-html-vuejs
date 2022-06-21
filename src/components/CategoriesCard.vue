<template>
    <div class="container">
       

        <ul>
        <li v-for="(item, i) in PopolarDishes " :key="i">
            <img :src="item.img" alt="">
            
            <div class="categoria"><b>{{item.categoria}}</b></div>
        </li>

    </ul>
    
    



    </div>
</template>

<script>
export default {
  data()  {
    return {
        PopolarDishes: [
            {
                img:require("../assets/img/appetizers-menu-background.jpg"),
                categoria:"Appetizers",             
            },
            {
                img:require("../assets/img/burgers-menu-background.jpg"),
                categoria:"Burgers",               
            },
            {
                img:require("../assets/img/pizza-menu-background.jpg"),
                categoria:" Pizzas",
            },
            {
                img:require("../assets/img/fries-menu-background.jpg"),
                categoria:"Fries",               
            },
            {
                img:require("../assets/img/sides-menu-background.jpg"),
                categoria:"Sides",              
            },
            {
                img:require("../assets/img/desserts-menu-background.jpg"),
                categoria:"Dessert",
            },
            {
                img:require("../assets/img/beverages-menu-background.jpg"),
                categoria:"Beverages",               
            },
            {
                img:require("../assets/img/specials-menu-background.jpg"),
                categoria:"Specials",
            }
        ]
    }



  }


}
</script>

<style scoped lang="scss">

    ul {
        display: flex;
        flex-wrap: wrap;
        color: white;
    }
    li {
        list-style-type: none;
        position: relative;
        width: 25%;
        height: 25%;
        
    }
    img {
        filter: brightness(50%);
        width: 100%;
        height: 100%;
    }
    .categoria {
        position: absolute;
        z-index: 2;
        top: 50%;
        left: 50%;
        transform: translate( - 50% - 50%);
    }


</style>