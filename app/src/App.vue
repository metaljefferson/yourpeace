<template>
  <div id="app">
    <Header/>
    <Section/>
    <Oracle/>
    <Relationship/>
    <Footer/>
  </div>
</template>

<script>
import Header from './components/Header.vue'
import Section from './components/Section.vue'
import Oracle from './components/Oracle.vue'
import Relationship from './components/Relationship.vue'
import Footer from './components/Footer.vue'
import './assets/styles/fonts.scss'
export default {
  name: 'App',
  components: {
    Header,
    Section,
    Oracle,
    Relationship,
    Footer
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
@import url('https://fonts.googleapis.com/css2?family=Aleo:ital@1&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Montserrat&display=swap');
</style>
