<template>

  <footer class="footer">

    <div style="max-width: 1170px; width: 100%; display: flex;">

      <div class="d-flex-column" style="flex-grow: 0;">

        <h5>Localização</h5>


        <iframe
          src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3714.5302824334276!2d-50.093463326614845!3d-21.408392083115878!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x949603fb4a3b8b8b%3A0x333adfc88f122a8!2sFerreira%20Engenharia%20e%20Constru%C3%A7%C3%B5es%20Ltda!5e0!3m2!1spt-BR!2sbr!4v1653850697872!5m2!1spt-BR!2sbr"
          width="360" height="250" style="border:0;" allowfullscreen="" loading="lazy"
          referrerpolicy="no-referrer-when-downgrade"></iframe>
      </div>

      <div class="d-flex-column" style="flex-grow: 1;">

        <h5>Fale Conosco</h5>

        <a href="https://goo.gl/maps/Ko1SAV2X5K9ETma17" target="_blank">
          <i class="fa fa-map-marker" aria-hidden="true"></i> Rua Vitor Antonio Janjácomo, 673. <br>
          Parque Industrial <br>
          CEP 16306-522 - Penápolis/SP
        </a>

        <a href="mailto:contato@ferreiraengenharia.com.br?subject=Olá">
          <i class="fa fa-envelope" aria-hidden="true"></i>contato@ferreiraengenharia.com.br
        </a>

        <a href="tel:+551836542030">
          <i class="fa fa-phone" aria-hidden="true"></i> (18) 3654-2030
        </a>

        <div class="d-flex-row" style="gap: 10px; font-size: 25px;">

          <a href="https://www.facebook.com/FerreiraEngenhariaOficial/">
            <i class="fa fa-facebook"></i></a>

          <a href="https://www.instagram.com/ferreiraengenharia/">
            <i class="fa fa-instagram"></i></a>

          <a href="https://www.youtube.com/user/FerreiraEngenhariaTV">
            <i class="fa fa-youtube-play"></i></a>

        </div>

      </div>

    </div>

    <small>
      Copyright © 2022 Ferreira Engenharia. Todos os direitos reservados.
    </small>


  </footer>
</template>

<script>
export default {
  name: 'FooterComponent',
  props: {

  }
}
</script>

   
<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.footer {
  color: #a9afb1;
  background-color: #192229;
  display: flex;
  flex-flow: row wrap;
  justify-content: center;
}

.footer>div {
  padding: 70px 0;
}

.footer>div>div {
  padding: 0 15px;
}

.footer>div>div h5 {
  color: #ffffff;
  font-weight: 700;
  margin: 20px 0 25px 0;
  font-size: 20px;
}

.footer>div>div>a {
  line-height: 1.5;
  margin-bottom: 20px
}

.footer>div>div>a i {
  margin-right: 10px
}


small {
  width: 100%;
  background-color: #212d36;
  padding: 15px 0;
  text-align: center;
  color: #a9afb1;
}
</style>
