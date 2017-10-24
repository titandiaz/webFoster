<template>
  <div id="app">
    <menu-top></menu-top>
    <banner-menu></banner-menu>
    <features-foster></features-foster> 
    <router-view/>
  </div>
</template>

<script>

import menuTop from './components/menu.vue'
import bannerMenu from './components/banner.vue' 
import featuresFoster from './components/features.vue'
export default {
  name: 'app',
  components: {
    menuTop,
    bannerMenu,
    featuresFoster
  }
}
</script>

<style>
html, body {
  color: #6b7c93;
  font-family: 'Roboto', sans-serif;
  padding: 0;
  margin: 0;
}
a {
  text-decoration: none;
}
#app {

  
  /* color: #2c3e50; */
}
</style>
