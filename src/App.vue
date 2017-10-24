<template>
  <div id="app">
    <menu-top></menu-top>
    <banner-menu></banner-menu>
    <router-view/>
  </div>
</template>

<script>

import menuTop from './components/menu.vue'
import bannerMenu from './components/banner.vue' 
export default {
  name: 'app',
  components: {
    menuTop,
    bannerMenu
  }
}
</script>

<style>
html, body {
  padding: 0;
  margin: 0;
}
a {
  text-decoration: none;
}
#app {

  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  color: #2c3e50;
}
</style>
