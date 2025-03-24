<script setup>
//importacion del card principal
import CardPrincipal from './CardPrincipal.vue';
//importacion del card 1
import Card from './Card.vue';
// metodos
</script>
<template>
 <!-- estructura html -->
  <!-- INICIO DEL CONTAINER -->
  <div class="container" style="background-color: #ffffed;">
    <!-- TITULO -->
    <br><h1 class="text-center">HTML, CSS Y JAVASCRIPT</h1><br>
    <!-- INICIO DEL PRIMER ROW -->
    <CardPrincipal/>
    <!-- CIERRE DEL PRIMER ROW -->
     <!-- INICIO DEL SEGUNDO ROW -->
      <Card/>
      <!-- CIERRE DEL SEGUNDO ROW -->
       <Card/>
  </div>
  <!-- CIERRE DEL CONTAINER -->

</template>
<style scoped>

</style>
