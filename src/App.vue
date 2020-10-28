<template>
  <div>
    <Formulario />
    <Pokeguia />
  </div>
</template>

<script>
import Formulario from './components/Formulario.vue';
import Pokeguia from './components/Pokeguia.vue';

export default {
  name: 'App',
  components: {
    Formulario,
    Pokeguia
  }
}
</script>

<style>

</style>
