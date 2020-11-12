<template>
  <footer>
    <div class="container">
      <div>
        <img :src="logoIcon"/>
        <div class="contact">
          <div>Call Us!</div>
          <div>45612-8121</div>
        </div>
      </div>
    </div>
  </footer>
</template>

<script>
import Logo from '../assets/images/logo.png';
import Menu from '../assets/images/menu.png';

export default {
  data(){
    return {
      logoIcon: Logo,
      menuIcon: Menu,
    }
  },
}
</script>

<style scoped>

</style>