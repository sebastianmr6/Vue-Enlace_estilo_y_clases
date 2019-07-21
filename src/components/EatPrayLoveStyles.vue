<template>
  <b-container :class="['p-3','text-white', fondo]">
    <h1 class="text-center mt-3">Comer, Rezar Amar 🍜✝❤</h1>
    <p class="text-center mt-3">Frases que inspiran</p>
    <ul>
      <li>Hay un chiste italiano buenísimo acerca de un hombre pobre que va al templo todos los días a rezarle a un santo. Reza a la estatua: Querido Santo por favor, por favor, por favor déjame ganar la lotería. Al final, la estatua desesperada cobra vida, baja la mirada y le dice al hombre: Hijo mío, por favor, por favor, por favor compra un billete. Ahora entiendo el chiste y tengo 3 billetes.</li>
      <li>Todo se viene abajo querida, lo único que permanece es la familia.</li>
      <li>Hay que ser cariñoso con uno mismo cuando se aprende algo nuevo.</li>
      <li>Sonríe con tu cara, con tu mente y hasta con el hígado.</li>
      <li>Trabaja la mente, es lo único que deberías de controlar, porque si no puedes controlar tus pensamientos estarás en problemas por siempre.</li>
    </ul>
    <p><strong>Nota:</strong> Puedes cambiar el color de fondo de esta tarjeta usando los colores de Bootstrap:</br>
      a) bg-primary</br>
      b) bg-secondary</br>
      c) bg-success</br>
      d) bg-danger</br>
      e) bg-warning</br>
      f) bg-info</br>
      g) bg-light</br>
      h) bg-dark</br>
      i) bg-white</br></p>
    <div class="input-group mb-3">
      <input
        type="text"
        v-model="fondo"
        class="form-control"
        placeholder="Ingresa el color de fondo"
        aria-label="Ingresa el color de fondo"
        aria-describedby="basic-addon2"
      >
      <button class="btn-danger btn-outline-dark" @click="fondo">Cambiar fondo</button>
    </div>
  </b-container>
</template>

<script>
export default {
  name: "EatPrayLoveStyles",
  data() {
    return {
      fondo: "bg-primary"
    };
  }
};
</script>

<style scoped>
</style>
