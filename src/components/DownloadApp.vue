<template>
  <div id="background">
    <div class="container">
        <h2>Download Our App</h2>
        <h1>Ordering App</h1>
        <img src="../assets/img/app-store-badge-200x67.png" alt="">
        <img src="../assets/img/play-store-badge-200x67.png" alt="">
    </div>
  </div>
</template>

<script>

</script>

<style scoped lang="scss">
    #background {
        height: 50vh;
        background-image: url(../assets/img/app-ordering-scaled.jpg);
        background-size: cover;
    }
    .container {
        width: 80%;
        margin: auto;
        position: relative;
        top: 40%;
    }
    img {
        margin: 5px;
    }
    h2 {
        color: white;
    }
    h1 {
        color: yellow;
        font-size: 65px;
    }
</style>