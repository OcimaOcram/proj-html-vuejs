<template>
    <div class="container">
        <div class="header">
            <img src="../assets/img/takeout-logo-2x-400x85.png" alt="">
            <ul>
                <li>
                    Home
                </li>
                <li>
                    Order Online
                </li>
                <li>
                    About
                </li>
                <li>
                    News
                </li>
                <li>
                    Contact Us
                </li>
            </ul>
        </div>
        <div id="hungry">
                <h2>Hungry?</h2>
                <h1> <div class="yellow">Great Food</div> Delivered</h1>
                <span class="button">
                    VIEW OUR MENU
                </span>




        </div>






    </div>
</template>

<script>


export default {
  
}
</script>

<style scoped lang="scss">
    .container {
        background-image: url(../assets/img/home-background-hero-scaled.jpg);
        background-size: 100%;
        background-position: center;
        height: 100vh;
    }
    .header {
        display: flex;
        justify-content: space-between;
        width: 80%;
        margin: auto;
    }
    img {
        width: 20%;
        height: 10%;
    }
    li {
        display: inline-block;
        margin: 15px;
        color: white;
    }

    #hungry {
        font-size: xx-large;
        width: 80%;
        margin: auto;
        color: white;
        margin-top: 30vh;

    }
    .yellow {
        color: #fcd66c
    }
    .button {
        background-color: #cc1a26;
        padding: 15px;
        border-radius: 30px;
        font-size: 15px;
    }




</style>
