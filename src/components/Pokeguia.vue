<template>
  <div>
      
  </div>
</template>

<script>
export default {
  name: 'Pokeguia',
  data () {
    return {
      imagen: "",
      movimientos: "",
      habilidades: ""
    }
  },
  methods: {
    beforeCreate() {
      console.log("before Create : ", this.message);
      },
    created() {
      fetch("https://pokeapi.co/api/v2/pokemon/")
      .then(response => response.json())
      .then(json => console.log(json));
    },
  }
}
</script>

<style>

</style>
