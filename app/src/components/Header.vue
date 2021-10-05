<template>
  <header>
    <Menu/>
  <h1 class="titulo">Find Your Peace
    <span class="subtitulo-1">Insight to nourish your spiritual path</span>
    <span class="subtitulo-2">$ 1 / min *</span>
  
   </h1>
  </header>
</template>

<script>
import Menu from './Menu.vue'

export default {
  name: 'Header',
  components: {
  Menu
  }
}
</script>

<style lang="scss">
header {
  color: orange;
  background-image: url('../assets/img/jesse-bowser-EkxO-SFU9kc-unsplash.jpg');
  height: 85vh;
  background-size: cover;
}
.titulo{
  font-family: Winter-Insight;
    font-size: 49px;
    text-align: center;
    line-height: 96.32%;
    font-weight: normal;
    width: 200px;
    margin-left: 26px;
 
}
.subtitulo-1{
      color: black;
    font-family: Winter-Insight;
    display: block;
    text-align: center;
    font-style: normal;
    font-weight: normal;
    font-size: 16px;
    text-transform: uppercase;
}
.subtitulo-2{
      font-family: Yrsa-Italic-VariableFont_wght;
    display: block;
    text-align: center;
    margin-top: 10px;
    font-size: 20px;
    line-height: 1px;
    text-transform: uppercase;
    letter-spacing: 0.1em;
    margin-top: 1px;

}
</style>
