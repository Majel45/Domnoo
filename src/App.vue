<template>
  <div>
    <Header/>
    <div>
      <Index/>
    </div>
    <Footer/>
  </div>
</template>

<script>
import Header from './components/Header.vue'
import Footer from './components/Footer.vue'
import Index from './components/Index.vue'

export default {
  components: {
    Header,
    Footer,
    Index,
  }
}
</script>

<style>
  @import './assets/style.css';
</style>
