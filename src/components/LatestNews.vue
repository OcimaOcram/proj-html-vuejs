<template>
    <div class="container">
        <div class="flex">
            <h1>
                Latest News
            </h1>
            <div class="button">
                <b>
                    READ MORE NEWS
                </b>
            </div>
        </div>
        <div class="flex">
            <div>
                <img src="../assets/img/pancake-burger-1200x900.jpg" alt="">
                <h1>
                    NEW: The Pancake Burger 
                </h1>
                <div class="grey">
                    Lorem ipsum dolor sit amet consectetur adipisicing elit. Iure ipsum eum nemo, voluptatibus nesciunt quibusdam iusto vitae repudiandae sunt cupiditate! Enim facere numquam sed qui maiores error id ab ex!
                </div>
            </div>
            <div>
                <img src="../assets/img/new-milkshake-menu-1200x900.jpg" alt="">
                <h1>
                    NEW Milkshake Menu 
                </h1>
                <div class="grey">
                    Lorem ipsum dolor sit amet consectetur adipisicing elit. Iure ipsum eum nemo, voluptatibus nesciunt quibusdam iusto vitae repudiandae sunt cupiditate! Enim facere numquam sed qui maiores error id ab ex!
                </div>
            </div>
        </div>
    </div>
</template>

<script>

</script>

<style scoped lang="scss">
.container {
    width: 80%;
    margin: auto;
    margin-top: 7%;
}
.flex {
    display: flex;
    justify-content: space-between;
}
.button {
    background-color: red;
    color: white;
    padding: 15px;
    font-size: small;
    border-radius: 50px;
}
img {
    width: 100%;
    padding: 20px;
}
.grey {
    color: grey;
}
</style>
