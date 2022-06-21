<template>
  <div id="app">
    <MyHeader/>
    <PopolarDishes/>
    <MenuCategories/>
    <DownloadApp/>
    <LatestNews/>
  </div>
</template>

<script>
import MyHeader from './components/MyHeader.vue';
import PopolarDishes from './components/PopolarDishes.vue';
import MenuCategories from './components/MenuCategories.vue';
import DownloadApp from './components/DownloadApp.vue';
import LatestNews from './components/LatestNews.vue';


export default {
  name: 'App',
  components: {
    MyHeader,
    PopolarDishes,
    MenuCategories,
    DownloadApp,
    LatestNews
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
