<template>
  <div id="home">
      <Botons></Botons>
      <Escena></Escena>
  </div>
</template>

<script>
import Escena from '@/components/Escena'
import Botons from '@/components/Botons'
import frases from "@/assets/json/historiaSideral.json";

export default {
    name: "Home",
    components: {
        Escena,
        Botons
    },
    props: ['frase'],

    computed: {
    frases() {
        return frases.map((frase) => {
            return frase
        })
    }
}

}
</script>

<style>

</style>