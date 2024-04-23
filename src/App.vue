<template>
  <main class="columns is-gapless is-multiline">
    <div class="column is-one-quarter">
      <BarraLateral />
    </div>
    <div class="column is-three-quarter">
      <FormularioPrincipal />
      <!-- Lista de Tarefas ???? -->
    </div>
  </main>
</template>

<script lang="ts">
import { defineComponent } from 'vue';
import BarraLateral from './components/BarraLateral.vue'
import Formulario from './components/Formulario.vue'
import FormularioPrincipal from './components/FormularioPrincipal.vue';

export default defineComponent({
  name: 'App',
  components: {
    BarraLateral,
    FormularioPrincipal
  }
});
</script>

<style>

</style>