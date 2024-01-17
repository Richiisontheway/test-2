<script>
// importazione del file
import Header from './components/Header.vue'
// my-component.js
export default {
  data() {
    return 
  },
  // aggiungo il nome del file come componente
  components: {
    Header
  }
}
</script>

<template>
      <!-- Aggiungo il tag con il nome del componente all'interno
        del tag template -->
      <Header />

      
</template>

<style scoped>

</style>
