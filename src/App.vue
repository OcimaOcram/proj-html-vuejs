<template>
  <div id="app">
    <MyHeader/>
    <PopolarDishes/>
    <MenuCategories/>
  </div>
</template>

<script>
import MyHeader from './components/MyHeader.vue';
import PopolarDishes from './components/PopolarDishes.vue';
import MenuCategories from './components/MenuCategories.vue';


export default {
  name: 'App',
  components: {
    MyHeader,
    PopolarDishes,
    MenuCategories
}
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  
  color: #2c3e50;
  
}
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
</style>
