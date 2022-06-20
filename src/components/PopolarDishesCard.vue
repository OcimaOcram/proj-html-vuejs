<template>
   <div class="container">
    
    
    <ul>
        <li v-for="(item, i) in PopolarDishes " :key="i">
            <img :src="item.img" alt="">
            
            <div>{{item.dishName}}</div>
            
            <div class="red">{{item.price}}</div>
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
                img:require("../assets/img/skin-on-fries-700x1000.jpg"),
                dishName:"Skin on Fries",
                price: "$ 3.00 - $ 6.00",
            },
            {
                img:require("../assets/img/choco-cookie-frappe-700x1000.jpg"),
                dishName:"Choco Cookie Frappe",
                price: "$4.99",
            },
            {
                img:require("../assets/img/donut-burger-700x1000.jpg"),
                dishName:" The Donut Burger",
                price: "$6.99",
            }
        ]
    }



  }


}
</script>

<style scoped lang="scss">

ul {
    width: 80%;
    margin: auto;
    display: flex;
}
li {
    list-style-type: none;
    margin: 15px;
}

img {
    width: 100%;
    
}
.red {
    color:red;
}

 
</style>