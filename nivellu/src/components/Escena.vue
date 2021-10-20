<template>
 <div>
     <!-- - Exercici 1 -->
     <div>El nostre heroi estava surant per l'espai sideral quan a la llunyania va albirar una nau espacial.</div>
     <div v-for="frase in frases" v-bind:key="frase.id">
         <div>{{ frase.sentencia }}</div>
     </div>
 </div>
</template>

<script>
import frases from "@/assets/json/historiaSideral.json";
export default {
name:'Escena',
props: {
    msg: String
},
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