<script setup>
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
    <div class="row">
      <!-- ¿QUE SON? -->
      <div class="col-md-6">
        <div class="card">
          <div class="card-header text-center" style="background-color: #fce5b1;">
              <h6>¿Qué son?</h6>
          </div>
          <div class="card-body text-justify">
            <p class="card-text">Son lenguajes de programación que se utilizan para crear páginas web,
              trabajan en conjunto para el contenido, considerados lenguajes front-end, es decir, se 
              ejecutan en el lado del usuario. </p>
          </div>
        </div>
      </div>
      <!-- FIN -->
       <!-- FUNCIONES -->
      <div class="col-md-6">
        <div class="card">
          <div class="card-header text-center" style="background-color: #fce5b1;">
              <h6>Funciones</h6>
          </div>
          <div class="card-body text-justify">
            <p class="card-text">HTML define la estructura de la pagina web y el contenido, CSS gestiona la presentación, 
              el diseño y estilo, y JavaScript añade interactividad, son fundamentales para crear páginas web. </p>
          </div>
        </div>
      </div>
      <!-- FIN -->
    </div>  
    <!-- CIERRE DEL PRIMER ROW -->
     <!-- INICIO DEL SEGUNDO ROW -->
      <Card/>
      <!-- CIERRE DEL SEGUNDO ROW -->
  </div>
  <!-- CIERRE DEL CONTAINER -->

</template>
<style scoped>

</style>
