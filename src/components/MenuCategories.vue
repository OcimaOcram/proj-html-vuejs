<template>
    <div>
        <div class="container">
            <h1>Menu Categories</h1>
            <div class="button">
                view the full menu
            </div>
        </div>
        <CategoriesCard/>
    </div>
</template>

<script>
import CategoriesCard from "./CategoriesCard.vue";

    



    export default {
        name: 'App',
        components: {
    CategoriesCard
    
}
    }
</script>

<style scoped lang="scss">
.container {
    width: 80%;
    margin: auto;
    display: flex;
    justify-content: space-between;
}
h1 {
    display: inline-block;
}
.button {
    display: inline-block;
    background-color: red;
    color: white;
    padding: 15px;
    border-radius: 30px;
    position: relative;
    bottom: 15px;
}

</style>