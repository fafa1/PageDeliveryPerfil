<template>
  <div class="main-flex">
    <div class="main-card" v-for="elemento in listaRestaurantes" :key="elemento.id">
      <div class="main-card-img">
        <img :src="elemento.imagem" width="50px" height="50px" alt="">
        <p>{{ elemento.tipo }}</p>
        <span id="primeiro"></span>
        <span></span>
        <span></span>
        <span></span>
        <span></span>
      </div>
      <div class="main-card-text">
        <h4>{{ elemento.tipo }}</h4>
        <p>{{ elemento.descricao }}:</p>
        <ul>
          <li><p>{{ elemento.passos }}</p></li>
        </ul>
      </div>
    </div>
    <div class="page-load">
      Carregar Mais
    </div>
  </div>
</template>

<script>
export default {
  name: 'boxCard',

  data() {
    return {
    }
  },

  props: ['listaRestaurantes']

}
</script>

<style scoped>
.main-flex {
  display: flex;
  flex-direction: column;
  align-items: center;
  /* justify-content: center; */
}

.main-card {
  display: flex;
  border: 1px solid #d5d5dac9;
  padding: 20px;
  width: 540px;
  margin-bottom: 2px;
  background-color: #fff;
}

.main-card-img img {
  margin-left: 15px;
}

.main-card-img p {
  margin-top: 3px;
  color: #333335c9;
  font-size: .9em;
}

#primeiro {
  display: inline-block;
  background-color: #e2e224;
  width: 8px;
  height: 8px;
  border-radius: 10px;
  margin-left: 3px;
}

.main-card-img span {
  content: '';
  display: inline-block;
  background-color: #cacac5;
  width: 8px;
  height: 8px;
  border-radius: 10px;
  margin-left: 3px;
}

.main-card-text {
  margin-left: 38px;
}

.main-card-text h4 {
  margin-bottom: 15px;
}

.main-card-text p {
  color: #333335c9;
}

.main-card-text li {
  margin-left: 15px;
}

.page-load {
  margin: 60px 0;
  border: 1px solid #828285c9;
  border-radius: 20px;
  padding: 5px;
  width: 540px;
  text-align: center;
  color: #333335c9;
}

</style>