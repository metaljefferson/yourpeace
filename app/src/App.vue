<template>
  <div id="app">
    <Header/>
    <Section/>
    
  </div>
</template>

<script>
import Header from './components/Header.vue'
import Section from './components/Section.vue'
import './assets/styles/fonts.scss'
export default {
  name: 'App',
  components: {
    Header,
    Section
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
@import url('https://fonts.googleapis.com/css2?family=Roboto:wght@400;500&family=Yrsa&display=swap');
</style>
