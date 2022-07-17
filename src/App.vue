<template>
  <div id="app">
    <DCHeaderNav/>
    <HeaderLink/>
    <DCMainExtension/>
    <DCMain/>
    <DCFooter/>
  </div>
</template>

<script>
import DCHeaderNav from './components/DCHeaderNav.vue'
import HeaderLink from './components/HeaderLink.vue'
import DCMainExtension from './components/DCMainExtension.vue'
import DCMain from './components/DCMain.vue'
import DCFooter from './components/DCFooter.vue'

export default {
  name: 'App',
  components: {
    DCHeaderNav,
    HeaderLink,
    DCMainExtension,
    DCMain,
    DCFooter,
  }
}
</script>

<style lang="scss">
  @import "~bootstrap/scss/bootstrap.scss";
  @import "./styles/variables.scss";
  
</style>
