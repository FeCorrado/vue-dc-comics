<template>
  <div id="app">
    <Header/>
    <Jumbo/>
    <Comics/>
    <Blu/>
    <Footermen/>
    <Footer/>
  </div>
</template>

<script>
import Header from './components/Header.vue'
import Jumbo from './components/Jumbo.vue'
import Comics from './components/Comics.vue'
import Blu from './components/Blu.vue'
import Footermen from './components/Footermen.vue'
import Footer from './components/Footer.vue'

export default {
  name: 'App',
  components: {
    Header,
    Jumbo,
    Comics,
    Blu,
    Footermen,
    Footer,
  }
}
</script>

<style lang="scss">
@import './style/main.scss';

</style>
