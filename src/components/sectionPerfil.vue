<template>
  <div class="header">
    <div class="page">
      <nav class="menu-nav">
        <ul>
          <li><a href="#">Rio de Janeiro, RJ</a></li>
          <li><a href="#">Prêmio WeSeek</a></li>
          <li><a href="#"> WeSeek News</a ></li>
          <li><a href="#"> Baixe o APP</a></li>
        </ul>
      </nav>
      <div class="login">
        <!-- <img src="" alt=""> -->
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