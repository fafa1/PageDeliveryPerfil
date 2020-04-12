<template>
  <div>
    <main class="main-body">
      <ul class="menu-main">
        <li><a href="#"> Todas</a></li>
        <li><a href="#"> Frequentador</a></li>
        <li><a href="#"> Amante</a></li>
        <li><a href="#"> Especialista</a></li>
        <li><a href="#"> Referência</a></li>
      </ul>

      <box-card :listaRestaurantes="restaurantes"></box-card>
    </main>
  </div>
</template>

<script>
import boxCard from './boxCard'
import imagem from '../assets/bebe.svg'
import imagem2 from '../assets/chefe-de-cozinha.svg'
export default {
  name: 'mainBody',

  components: {
    boxCard
  },

  data() {
    return {
      restaurantes: [
        {tipo: 'churrascaria', imagem, descricao: 'Para se tornar amante você precisa', passos: 'Avaliar 3 restaurantes.(1/3)' },
        {tipo: 'Choppeira', imagem: imagem2, descricao: 'Para se tornar amante você precisa', passos: 'Avaliar 3 restaurantes.(1/3)' },
        {tipo: 'Pizzaria', imagem: imagem2, descricao: 'Para se tornar amante você precisa', passos: 'Avaliar 3 restaurantes.(1/3)' },
        {tipo: 'Saúdavel', imagem: imagem2, descricao: 'Para se tornar amante você precisa', passos: 'Avaliar 3 restaurantes.(1/3)' },
        {tipo: 'Doceira', imagem: imagem2, descricao: 'Para se tornar amante você precisa', passos: 'Avaliar 3 restaurantes.(1/3)' },
        {tipo: 'churrascaria', imagem, descricao: 'Para se tornar amante você precisa', passos: 'Avaliar 3 restaurantes.(1/3)' },
        {tipo: 'Choppeira', imagem: imagem2, descricao: 'Para se tornar amante você precisa', passos: 'Avaliar 3 restaurantes.(1/3)' },
        {tipo: 'Pizzaria', imagem, descricao: 'Para se tornar amante você precisa', passos: 'Avaliar 3 restaurantes.(1/3)' },
        {tipo: 'Choppeira', imagem: imagem2, descricao: 'Para se tornar amante você precisa', passos: 'Avaliar 3 restaurantes.(1/3)' },
        {tipo: 'Pizzaria', imagem, descricao: 'Para se tornar amante você precisa', passos: 'Avaliar 3 restaurantes.(1/3)' },
        {tipo: 'Choppeira', imagem: imagem2, descricao: 'Para se tornar amante você precisa', passos: 'Avaliar 3 restaurantes.(1/3)' },
        {tipo: 'Pizzaria', imagem, descricao: 'Para se tornar amante você precisa', passos: 'Avaliar 3 restaurantes.(1/3)' },
        {tipo: 'Choppeira', imagem: imagem2, descricao: 'Para se tornar amante você precisa', passos: 'Avaliar 3 restaurantes.(1/3)' },
        {tipo: 'Pizzaria', imagem,descricao: 'Para se tornar amante você precisa', passos: 'Avaliar 3 restaurantes.(1/3)' },
        {tipo: 'Doceira', imagem: imagem2, descricao: 'Para se tornar amante você precisa', passos: 'Avaliar 3 restaurantes.(1/3)' }
      ]
    }
  }
}
</script>

<style scoped>

.menu-main {
  display: flex;
  justify-content: center;
  padding: 40px 0;
}

.menu-main li {
  margin-right: 30px;
  list-style: none;
  border: 1px solid #d5d5dac9;
  background-color: #929296c9;
  border-radius: 30px;
  padding: 8px 0;
  width: 130px;
  text-align: center;
}
.menu-main li:first-child {
  background-color: #993535;
}

.menu-main a {
  color: #fff;
  font-weight: bold;
}
</style>