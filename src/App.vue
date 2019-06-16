<template>
  <div id="app">
    <!-- <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/> -->
    <MyNav></MyNav>
    <BigSection></BigSection>
    <ShopList></ShopList>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import ShopList from './components/ShopList.vue'
import MyNav from './components/MyNav.vue'
import BigSection from './components/BigSection.vue'

export default {
  name: 'app',
  components: {
    HelloWorld,
    ShopList,
    MyNav,
    BigSection
  }
}
</script>

<style>
#app {
  font-family: '微軟正黑體';
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  /* color: #2c3e50; */
  margin: 0;
  padding: 0;
  /* margin-top: 60px; */
}
</style>
