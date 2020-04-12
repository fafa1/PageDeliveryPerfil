<template>
  <div class="page">
    <div class="footer">
      <div class="footer-copy">
        <img src="../assets/mortarboard.svg" width="50px" height="50px" alt="">
        <p>A maior rede social para amantes de gastronomia!</p>
        <div class="footer-copy-text">
          <p>Copyrigth @2017 WESEEK FOOD</p>
        </div>
      </div>
      <div class="footer-list">
        <ul>
          <li>Contato</li>
          <li>Política de Privacidade</li>
          <li>Quem Somos</li>
          <li>Termo de Uso</li>
          <li>Política de Cancelamento</li>
        </ul>
      </div>
      <div>
        <img src="../assets/facebook.png" width="100px" height="100px" alt="facebook">
      </div>
      <div class="footer-appstore">
        <h2>Baixe o App!</h2>
        <img src="../assets/appStore.png" width="300px" height="50px" alt="appStore">
      </div>
    </div>
  </div>
</template>

<script>
export default {
  
}
</script>

<style scoped>
.page {
  background-color: #1d1c1c;
}

.footer {
  margin: 0 auto;
  max-width: 1100px;
  display: flex;
  justify-content: space-between;
  padding: 60px 0;
  color: #fff;
}

.footer-copy > p {
  color: #df8d23;
  margin-bottom: 35px;
  text-transform: uppercase;
  font-size: .9em;
}

.footer-copy-text {
  font-size: .9em;
}

.footer-list {
  margin-top: 10px;
  font-size: .9em;
}

.footer-appstore h2 {
  margin-bottom: 10px;
}
</style>