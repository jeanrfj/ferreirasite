<template>
  <header class="header">

    <a href="">

      <img src="@/assets/logo.png" alt="">

      <h1 style="font-size: 0;">
        Ferreira Engenharia
      </h1>

    </a>

    <ul>

      <li>
        <a href="">
          Home
        </a>
      </li>

      <li>
        <a href="">
          Quem somos
        </a>
      </li>

      <li>
        <a href="">
          Áreas de atuação
          <i class="fa fa-angle-down" aria-hidden="true"></i>
        </a>

      </li>

      <li>
        <a href="">
          Imóveis a venda
        </a>
      </li>

      <li>
        <a href="">
          Contato
        </a>
      </li>

      <li>
        <a href="">
          Portal do Cliente
        </a>
      </li>


      <li>
        <a href="">
          Política e Privacidade
        </a>
      </li>

    </ul>

  </header>
</template>

<script>
export default {
  name: 'HeaderComponent',
  props: {

  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.header {
  display: flex;
  justify-content: center;
  align-items: center;
  background: white;
  gap: 30px;
  box-shadow: 0 0 15px 1px rgb(0 0 0 / 7%);
}

.header ul {
  display: flex;
  align-items: center;
}

.header ul li a {
  padding: 15px
}

.header ul li a:hover {
  color: #FE0000;
}
</style>
