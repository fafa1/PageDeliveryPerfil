<template>
  <div class="header-up">
    <div class="page">
      <section class="main-perfil">
        <div class="perfil-header">
          <div class="perfil-img">
            <img src="../assets/thorRagnar.jpg" width="150px" height="150px" alt="thor">
          </div>
          <div class="perfil-status-texto">
            <h2>almightyThor</h2>
            <p>Baby Sage</p>
            <div class="perfil-status">
              <p><span>11.712</span> Pontos</p>
              <p><span>97</span> seguidores</p>
              <p><span>105</span> seguindo</p>
            </div>
            <p>
              Do mesmo modo, a consulta aos diversos militantes obstaculiza
              a apreciação da importância do levantamento das variáveis envolvidas.
            </p>
          </div>
        </div>
        <div class="perfil-status-nivel">
          <h3>Nível do foodie</h3>
          <ul>
            <li>
              <img src="../assets/bebe.svg" width="40px" height="33px" alt="">
              <span>Baby Stage</span>
            </li>
            <li>
              <img src="../assets/foguete.svg" width="50px" height="40px" alt="">
              <span>Bom Vivant</span>
            </li>
            <li>
              <img src="../assets/mortarboard.svg" width="50px" height="40px" alt="">
              <span>Nome</span>
            </li>
            <li>
              <img src="../assets/restaurante.svg" width="50px" height="45px" alt="">
              <span>Gourmand</span>
            </li>
            <li>
              <img src="../assets/chefe-de-cozinha.svg" width="50px" height="40px" alt="">
              <span>Conncisseur</span>
            </li>
          </ul>
        </div>
        <div class="perfil-status-config">
          <span>
            <p>Editar Informações</p>
          </span>
          <div>
            <a href="#">bfagner@hotmail.com</a>
            <a href="#">www.google.com.br</a>
            <a href="#">+5571983930033</a>
            <a href="#">batistaFagner</a>
            <a href="#">@fagner</a>
          </div>
        </div>
      </section>
      <div class="container-menu">
        <ul>
          <li><a href="#">Ranking Pessoal</a></li>
          <li><a href="#">Mapa Gastronômico</a></li>
          <li><a href="#">Avaliações</a></li>
          <li><a href="#">Wishlist</a></li>
          <li><a href="#">Curtidas</a></li>
          <li id="text-color"><a href="#">Especialidades</a></li>
        </ul>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'headerUp'
}
</script>

<style scoped>
.header-up {
  background-color: #fff;
  box-shadow: 0px 10px 3px -5px #e2dfdf
}

.page {
  margin: 0 auto;
  max-width: 1100px;
}

.main-perfil {
  display: flex;
  justify-content: space-between;
  padding: 20px 0;
  border-bottom: 1px solid #d5d5dac9;
}

.perfil-header {
  display: flex;
}

.perfil-img img {
  margin-right: 25px;
  border-radius: 50%;
}

.perfil-status {
  display: flex;
}

.perfil-status p {
  padding-top: 18px;
  padding-right: 20px;
}

.perfil-status ~ p {
  width: 350px;
  margin-top: 30px;
}

.perfil-status span {
  font-weight: bold;
}

.perfil-status-nivel li {
  display: inline-block;
  margin-right: 10px;
}

.perfil-status-nivel span {
  display: block;
}

.perfil-status-config span {
  display: block;
  border: 1px solid black;
  border-radius: 20px;
  width: 180px;
  height: 20px;
}

.perfil-status-config span p {
  padding-left: 30px;
}

.perfil-status-config a {
  display: block;
  line-height: 25px;
  color: #e09a32;
}

.perfil-status-config div {
  margin-top: 20px;
}

.container-menu ul {
  display: flex;
  justify-content: space-between;
  list-style: none;
  padding: 30px 0;
}

.container-menu a {
  color: #656568c9;
}

#text-color a {
  color: #cc2121;
}

</style>