<template>
  <figure class="banner-container">
    <img src="https://ferreiraengenharia.com.br/wp-content/uploads/2021/09/Banner_Site.png" alt="">

    <img src="https://ferreiraengenharia.com.br/wp-content/uploads/2022/02/slide_salto_correto.jpg" alt=""
      style="display: none;">

  </figure>
</template>

<script>
export default {
  name: 'BannerComponent',
  props: {

  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.banner-container {
  display: flex;
  justify-content: center;
  max-width: 1500px;
  height: 33vw;
  max-height: 500px;
  margin: 0 auto
}

.banner-container img {
  width: 100%;
  height: 100%;
}

@media screen and (max-width: 1500px) {

  .banner-container {
    max-width: unset;
    height: 33vw;
    width: 100%;
  }

}
</style>
