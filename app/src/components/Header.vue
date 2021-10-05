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
  height: 100vh;
  background-position: center;
}
.titulo{
  font-family: Winter-Insight;
    font-size: 135px;
    text-align: center;
    line-height: 96.32%;
    font-weight: normal;
    width: 494px;
    margin-left: 26px;
 
}
.subtitulo-1{
      color: black;
    font-family: Winter-Insight;
    display: block;
    text-align: center;
    font-style: normal;
    font-weight: normal;
    font-size: 30px;
    line-height: 38px;
    text-transform: uppercase;
    letter-spacing: 0.1em;
    width: 428px;
    margin-left: 26px;
    margin-top: 30px;
}
.subtitulo-2{
    font-family: Yrsa-Italic-VariableFont_wght;
    display: block;
    text-align: center;
    margin-top: 10px;
    font-size: 64px;
    line-height: 38px;
    letter-spacing: 0.1em;
    margin-top: 25px;

}
</style>
