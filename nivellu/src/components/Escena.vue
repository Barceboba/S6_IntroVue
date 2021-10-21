<template>
 <div id=container>
     <!-- - Exercici 1 -->
<!--      <div>El nostre heroi estava surant per l'espai sideral quan a la llunyania va albirar una nau espacial.</div> -->

<!-- Exercici 2 -->
     <div v-for="frase in frases" v-bind:key="frase.id">
         <div id="frase">{{ frase.sentencia }}</div>
     </div>
 </div>
</template>

<script>
/* import frases from "@/assets/json/historiaSideral.json"; */
export default {
name:'Escena',
/* props: {
    msg: String
}, */
/* computed: {
    frases() {
        return frases.map((frase) => {
            return frase
        })
    }
} */
emits: ['frase', 'sentencia']
}
</script>

<style>
/* Exercici 3 */
#frase {
    display: inline-block;
    border: 2px solid black;
    border-radius: 50em;
    padding: 10px;
    margin-bottom: 15px;
    width: 800px;

}
/* #container {
    display: flexbox;
   align-items: center;
     align-self: center;


} */

</style>