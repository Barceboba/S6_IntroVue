<template>
  <div id="home">
      <Botons></Botons>
      <Escena></Escena>
  </div>
</template>

<script>
import Escena from '@/components/Escena'
import Botons from '@/components/Botons'

export default {
    name: "Home",
    components: {
        Escena,
        Botons
    }

}
</script>

<style>

</style>