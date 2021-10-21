<template>
  <div id="app">
    <img alt="Vue logo" src="@/assets/logo.svg" width="200px">
    <Home></Home>
  </div>
</template>

<script>
import Home from '@/components/Home.vue'

export default {
  name: 'App',
  components: {
    Home
  /* },
  computed: {
    frases() {
        return frases.map((frase) => {
            return frase
        })
    }*/
} 
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
