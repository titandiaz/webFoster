<template>
  <div class="section-experts">
      <div class="container-section-experts">
        <div class="container-one">
            <img src="../assets/toggle-button-copy.png" alt="">
            <h1 class="subtitle-experts">Expertos en Tecnología</h1>
            <p class="description-one">Stripe is an always-improving toolchain that gains new features every month. Our world-class engineering team constantly iterates upon every facet of the Stripe stack. And from Apple Pay to Bitcoin, building on Stripe means you get early access to the latest technologies.</p>
        </div>
        <div class="container-one">
            <img src="../assets/toggle-button-copy.png" alt="">
            <h1 class="subtitle-experts">Desarrollos Corporativos</h1>
            <p class="description-one">We help power 100,000+ businesses in 100+ countries and across nearly every industry. Headquartered in San Francisco, Stripe has 9 global offices and hundreds of people working to help transform how modern businesses are built and run</p>
        </div>
      </div>
  </div>
</template>

<script>
export default {

}
</script>

<style>
.subtitle-experts {
    font-size: 21px;
    color:#24b47e;
    letter-spacing: 1.5px;
    font-weight: normal;
}
.section-experts {
    display: flex;
    justify-content: center;
    align-items: center;
    width: 100%;
    height: 600px;
    background-color: #E8F0F8;
}
.container-section-experts {
    width: 1300px;
    display: flex;
    justify-content: space-around;
}
.container-one {
    width: 535px;
}
.description-one {
    font-size: 21px;
    line-height: 1.5;
}

</style>
