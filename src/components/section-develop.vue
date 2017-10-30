<template>
  <div class="section-develop">
    <div class="container-section-develop">
      <img src="../assets/salesforce-ipad.png" alt="imagen table" class="image-develop">
      <div class="container-description-develop">
        <h2 class="title-section">Desarrollamos sus ideas</h2>
        <a href="#" class="link-subtitle"> &#9658; Nuestros Proyectos</a>         
        <p class="description-section">Nuestro equipo de profesionales en diferentes areas de tecnologia, es uno de los principales referentes creando soluciones, productos y servicios de alta calidad. Creamos proyectos que dan valor a la vida de nuestros clientes, nos enfocamos en innovar y utilizar poderesos herramientas para desarrollar tus ideas.</p>
        <button class="btn-white">Nosotros</button>       
      </div>
    </div>
  </div>
</template>

<script>
export default {

}
</script>

<style>
.section-develop {
  padding: 40px 0;
  margin-top: 60px;
  background-color: #E8F0F8;
}
.image-develop {
  width: 400px;
  margin-right: 3%;
}

.container-description-develop {
  width: 670px;
  margin-left: 3%;
}

.container-section-develop {
  text-align: right;
  min-height: 600px;
  display: flex;
  justify-content: center;
  align-items: center;
  flex-wrap: wrap;
  padding-right: 30px;
  padding-left: 30px;
}
.link-subtitle {
  font-size: 11px;
  color: #4b74ff;
  text-transform: uppercase;
  font-family: 'Roboto', sans-serif;
}
.description-section {
  font-size: 21px;
  line-height: 1.5;
}

</style>
