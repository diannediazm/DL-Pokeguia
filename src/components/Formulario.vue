<template>
    <div class="background">
        <img :src="require('../assets/images/pokemon.png')" />
        <h3>PokeGuía</h3>
        <form>
        <div class="form-group text-white">
            <label for="pokemon">Ingresa el número de un Pokémon</label>
            <input type="text" class="form-control">
        </div>
        <button type="submit" class="btn btn-primary bg-warning">¡Buscar!</button>
        </form>
    </div>
</template>

<script>
export default {
    name: 'Formulario'
}
</script>

<style>
.background {
    background-image: url('../assets/images/background.jpg');
    background-size: cover;
    height: 1000px;
}
img {
  width: 500px;
  display: block;
  margin: 0 auto;
  padding-top: 60px;
}
h3 {
  text-align: center;
  color: white;
}
form {
  width: 50%;
  display: block;
  margin: 0 auto;
  margin-top: 60px;
}
</style>