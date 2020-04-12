<template>
  <div class="section-header">
    <section class="page">
      <nav class="menu-nav-header">
        <ul class="menu-nav-lista">
          <li>
            <a href="#">
              <img src="../assets/seekFood.png" width="100px" height="40px" alt="">
            </a>
          </li>
          <li><input type="text" placeholder="Buscar restaurantes..."></li>
          <li>
            <a class="nav-text" href="#">
              <span>
                <img src="../assets/logo/talheres.svg"
                width="20px" height="20px" alt="">
                restaurantes
              </span>
            </a>
          </li>
          <li>
            <a class="nav-text-foodie" href="#">
              <span>
                <img src="../assets/logo/estrela-do-mar.svg"
                width="20px" height="20px" alt="">
                Foodies
              </span>
            </a>
          </li>
        </ul>
      </nav>
    </section>
  </div>
</template>

<script>
export default {
}
</script>

<style scoped>
.section-header {
  background-color: #fff;
  border-bottom: 1px solid #d5d5dac9;
  box-shadow: 0px 1px 4px 0px #e2dfdf;
}

.page {
  margin: 0 auto;
  max-width: 960px;
}

.menu-nav-header {
  padding: 20px 0;
}

.menu-nav-header a {
  text-decoration: none;
}

.menu-nav-lista {
  display: flex;
  justify-content: space-between;
}

.menu-nav-lista input {
  width: 33vw;
  border: 1px solid #d5d5dac9;
  box-shadow: 0px 1px 2px 0px #b1adad;
  box-sizing: border-box;
  height: 28px;
  outline: none;
  padding: 0 20px;
  border-radius: 10px;
}

.nav-text {
  color: #79797cc9;
  text-transform: uppercase;
  font-size: .9em;
  font-weight: bold;
  letter-spacing: -1px;
  padding-bottom: 10px;
}

.nav-text span {
  margin-right: 10px;

}

.nav-text-foodie {
  color: #da2a2a;
  text-transform: uppercase;
}
</style>