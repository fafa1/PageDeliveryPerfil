<template>
  <div>
    <section-perfil/>
    <section-header/>
      <header-up></header-up>
      <!-- <main-body></main-body> -->
  </div>
</template>

<script>
import headerUp from './headerUp'
import mainBody from './mainBody'
import sectionPerfil from './sectionPerfil'
import sectionHeader from './sectionHeader'

export default {
  name: 'HelloWorld',

  components: {
    sectionPerfil,
    sectionHeader,
    headerUp,
    mainBody
  },


  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
