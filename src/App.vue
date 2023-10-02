<template>
  <div id="app">
   
    <HeaderComponent/>
    <BannerComponent/>
    <PostComponent/>    
    <ArticlesComponent/>
    <PaginationComponent/>
    <FooterComponent/>
  </div>
</template>

<script>

import HeaderComponent from './components/HeaderComponent.vue'
import BannerComponent from './components/BannerComponent.vue'
import PostComponent from './components/PostComponent.vue'
import ArticlesComponent from './components/ArticlesComponent.vue'
import FooterComponent from './components/FooterComponent.vue'
import PaginationComponent from './components/PaginationComponent.vue'




export default {
  name: 'App',
  components: {
    HeaderComponent,BannerComponent,PostComponent,FooterComponent,ArticlesComponent,PaginationComponent
   
  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
