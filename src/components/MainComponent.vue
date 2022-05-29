<template>

  <main class="home-main d-flex-column a-center">

    <article class="d-flex-row wrap j-center a-center">

      <section class="d-flex-column a-center">
        <img src="@/assets/icone-ferreira-engenharia.png" alt="">
        <h4>Incorporação Imobiliária</h4>
        <p>Com forte atuação desde 2008 no mercado de Incorporação Imobiliária, somos responsáveis pelos maiores cases
          de
          sucesso do setor na região de Araçatuba.</p>
      </section>

      <section class="d-flex-column a-center">
        <img src="@/assets/icone-ferreira-engenharia.png" alt="">
        <h4>Desenvolvimento Urbano</h4>
        <p>Atuamos no mercado de loteamentos fechados de alto padrão e loteamentos abertos, respeitando o meio ambiente
          e
          o desenvolvimento social da comunidade em que estão inseridos.</p>
      </section>

      <section class="d-flex-column a-center">
        <img src="@/assets/icone-ferreira-engenharia.png" alt="">
        <h4>Shopping Centers</h4>
        <p>Percebendo o potencial de mercado do setor, desenvolvemos um modelo de baixo custo de implantação e operação
          com o objetivo de trazer satisfação aos lojistas e consumidores.</p>
      </section>

    </article>

    <article class="d-flex-row wrap j-center">

      <figure class="d-flex-row j-center a-center">
        <img src="@/assets/destaque-400x400.jpg" alt="">
        <figcaption>NY Tower</figcaption>
      </figure>

      <figure class="j-center a-center">
        <img src="@/assets/Destaque-2-1-400x400.jpg" alt="">
        <figcaption>Duetto Boulevard</figcaption>
      </figure>

      <figure class="j-center a-center">
        <img src="@/assets/Destaque-3-400x400.jpg" alt="">
        <figcaption>Residencial Firenze</figcaption>
      </figure>

    </article>

  </main>

</template>

<script>
export default {
  name: 'MainComponent',
  props: {
    // msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.home-main {
  max-width: 1170px;
  width: 100%;
  margin: 0 auto;
  padding: 70px 0;
}

.home-main article section {
  max-width: 380px;
  text-align: center;
  padding: 0 15px;
}

.home-main article section h4 {
  margin: 26px 0;
  font-size: 26px;
  font-weight: 500;
}

.home-main article section p {
  line-height: 1.5;
  color: #777777;
}

.home-main article figure {
  max-width: 380px;
  position: relative;
}

.home-main article figure figcaption {
  visibility: hidden;
  position: absolute;
  left: 50%;
  top: 50%;
  transform: translate(-50%, -50%);
  color: #000;
  font-size: 8px;

}

.home-main article figure:hover img {
  opacity: .1;
  cursor: pointer;
}

.home-main article figure:hover figcaption {
  visibility: visible;
  font-size: 16px;
  transition: all 0.25s;
}
</style>

