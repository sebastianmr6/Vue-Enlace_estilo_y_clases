<template>
  <b-container class="p-3 text-white" :class="{'bg-warning':color, 'bg-info':!color}">
    <h1 class="text-center mt-3">Kung Fu Panda 🐼</h1>
    <p class="text-center mt-3">Frases que inspiran</p>
    <ul>
      <li>El ayer es historia, el mañana es un misterio, pero hoy es un regalo. Por eso lo llaman presente.</li>
      <li>Tu mente es como el agua, mi amigo. Cuando se agita, es difícil ver. Pero si permites que se asiente, la respuesta se hace evidente.</li>
      <li>No hay un ingrediente secreto. Eres solo tú.</li>
      <li>Sirve con una sonrisa.</li>
      <li>Lo único que importa es en lo que tú decides convertirte.</li>
    </ul>
    <button class="btn btn-outline-dark" @click="color= !color">Cambiar</button>
  </b-container>
</template>

<script>
export default {
  name: "KungFuPandaStyle",
  data() {
    return {
      color: true
    }
  }
};
</script>

<style scoped>
</style>
