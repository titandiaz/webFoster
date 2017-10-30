<template>
  <div class="footer">
      <img src="../assets/top-banner.png" alt="Logo Foster" class="logo-foster-footer">
      <p class="description-footer">Desarrollado en Colombia por mentes creativas</p>
      <p class="copyright description-footer">@Copiright FosterApps 2017</p>
  </div>
</template>

<script>
export default {

}
</script>

<style>
.footer {
    background-image: url('../assets/commfooter-geninteresttutorials.png');
    background-position: 50%;
    height: 150px;
    background-size: cover;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;

}
.description-footer {
    color: #fff;
    text-align: center;
    margin: 0;
    font-size: 18px;
}
.logo-foster-footer {
width: 80px;
padding-bottom: 10px;
}

</style>
