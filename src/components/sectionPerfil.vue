<template>
  <div class="header">
    <div class="page">
      <nav class="menu-nav">
        <ul>
          <img src="../assets/logoSuperior/pin.svg" width="25px" height="15px" alt="">
          <li><a href="#">Rio de Janeiro, RJ</a></li>
          <li><a href="#">Prêmio WeSeek</a></li>
          <li><a href="#"> WeSeek News</a ></li>
          <li><a href="#"> Baixe o APP</a></li>
          <img src="../assets/logoSuperior/marca.svg" width="25px" height="15px" alt="">
          <img src="../assets/logoSuperior/loja-de-jogos.svg" width="25px" height="12px" alt="">
        </ul>
      </nav>
      <div class="login">
        <img src="../assets/logoSuperior/conecte-se.svg" width="25px" height="20px" alt="">
        <p><img src="" alt=""></p>
        <p>Olá visitante Faça seu login.</p>
      </div>


    </div>
  </div>
</template>

<script>
export default {
  name: 'arquivo1'
}
</script>

<style scoped>
.header {
  padding: 5px 0;
  background-color: #af2828;
}

.page{
  margin: 0 auto;
  max-width: 960px;
  display: flex;
  justify-content: space-between;
}

/* .menu-nav {
  margin-right: 20px;
} */

.menu-nav li {
  display: inline-block;
  margin-right: 15px;
}

.menu-nav a {
  color: #fff;
  font-size: .9em;
}

.login {
  display: flex;
}

.login p {
  color: #fff;
  font-size: .9em;
}
</style>