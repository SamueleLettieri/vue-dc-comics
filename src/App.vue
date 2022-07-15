<template>
  <div id="app">
    <DCHeaderNav/>
    <HeaderLink/>
    <DCMain/>
    <DCFooter/>
  </div>
</template>

<script>
import DCMain from './components/DCMain.vue'
import DCHeaderNav from './components/DCHeaderNav.vue'
import HeaderLink from './components/HeaderLink.vue'
import DCFooter from './components/DCFooter.vue'

export default {
  name: 'App',
  components: {
    DCHeaderNav,
    HeaderLink,
    DCMain,
    DCFooter,
  }
}
</script>

<style lang="scss">
  @import "~bootstrap/scss/bootstrap.scss";
  @import "./styles/variables.scss";
  
</style>
