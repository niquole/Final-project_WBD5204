<template>
  <div id="app">
    <Header/>


    <Footer/>
  </div>
</template>

<script>
import Home_Client from './views/Home_Client.vue'
import Header from './components/Header.vue'
import Footer from './components/Footer.vue'



export default {
  name: 'app',
  components: {
    Home_Client,
    Header,
    Footer
  }
}
</script>

<style lang="scss">
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  text-align: center;

}
</style>
