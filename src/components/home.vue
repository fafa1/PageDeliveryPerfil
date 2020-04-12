<template>
  <div>
    <section-perfil/>
    <section-header/>
    <header-up/>
    <main-body/>
    <footer-view/>
  </div>
</template>

<script>
import headerUp from './headerUp'
import mainBody from './mainBody'
import sectionPerfil from './sectionPerfil'
import sectionHeader from './sectionHeader'
import footerView from './footerView'

export default {
  name: 'home',

  components: {
    sectionPerfil,
    sectionHeader,
    headerUp,
    mainBody,
    footerView
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
