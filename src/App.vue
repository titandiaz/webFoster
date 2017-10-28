<template>
  <div id="app">
    <menu-top></menu-top>
    <banner-menu></banner-menu>
    <features-foster></features-foster> 
    <router-view/>
    <section-develop></section-develop>
    <section-technologies></section-technologies>
    <section-experts></section-experts>
  </div>
</template>

<script>

import menuTop from './components/menu.vue'
import bannerMenu from './components/banner.vue' 
import featuresFoster from './components/features.vue'
import sectionDevelop from './components/section-develop.vue'
import sectionTechnologies from './components/section-technologies.vue'
import sectionExperts from './components/section-experts.vue'
export default {
  name: 'app',
  components: {
    menuTop,
    bannerMenu,
    featuresFoster,
    sectionDevelop,
    sectionTechnologies,
    sectionExperts
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
.title-section {
  color: #4a4a4a;
  font-family: 'Open Sans', sans-serif;
  font-size: 45px;
  font-weight: normal;
  letter-spacing: 0.5px;
  margin: 0;
}

.btn-blue {
  font-family: 'Open Sans', sans-serif;
  font-weight: 600;
  color: #fff;
  padding: .8em 3em;
  background-color: #4b74ff;
  border: 0;
  border-radius: 2px;
}
.btn-white {
  font-family: 'Open Sans', sans-serif;
  font-weight: 600;
  color: #4b74ff;
  padding: .8em 3em;
  background-color: #fff;
  border: 0;
  border-radius: 2px;
  box-shadow: 0px 1px 5px #999;
}
.description-section {
  font-size: 20px;
}
#app {

}
  
  /* color: #2c3e50; */

</style>
