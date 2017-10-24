<template>
  <div class="menu">
    <img src="../assets/top-banner_2.png" class="logo-foster" alt="logo foster">
    <nav class="menu-navigation">
      <ul class="list-menu">
        <li class="item-menu"><a href="#" class="link-item-menu">Inicio</a> </li>
        <li class="item-menu"><a href="#" class="link-item-menu">Nosotros</a> </li>
        <li class="item-menu"><a href="#" class="link-item-menu">Portafolio</a> </li>
        <li class="item-menu"><a href="#" class="link-item-menu">Blog</a> </li>
      </ul>
    </nav>
    <!-- <div class="buttons-contact">
      <div class="container-buttons-contact">
        <div class=" btn-contact btn-lenguage"><img src="../assets/flag-col.png" alt=""></div>
        <div class=" btn-contact btn-facebook"><img src="../assets/facebook.png" alt=""></div>
        <div class=" btn-contact btn-contact"><img src="../assets/phone-icon-2.png" alt=""></div>
      </div>
    </div> -->
  </div>
  
</template>

<script>
export default {};
</script>

<style>
.logo-foster {
  margin-left: 50px;
  height: 60px;
}
.menu {
    background-color: #f9fafb;
    display: flex;
    align-items: center;
    max-width: 100%;
    height: 80px;
}

.menu-navigation {
  align-self: center;
  width: 400px;
  height: auto;
  padding-left: 50px;
}

.list-menu {
  display: flex;
  padding: 0;
  margin: 0;
  list-style: none;
  justify-content: space-between;
  font-weight: bold;
}
.buttons-contact {
  width: 200px;
  height: auto;
}
.container-buttons-contact {
  display: flex;
  
  /* justify-content: space-between; */
  /* align-items: center; */
}
.btn-contact {
  margin-left: 20px;
}
/* .btn-facebook {
  border: 1px solid blue;
  border-radius: 50%;
  padding: 10px 10px;
} */
.link-item-menu {
  color: #2c3e50;
  padding: 1em;
}
</style>
