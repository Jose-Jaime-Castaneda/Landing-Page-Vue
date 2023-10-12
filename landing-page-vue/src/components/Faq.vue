<template>
  <section>
    <div class="faq">
      <article class="encabezado">
        <h2>P&R</h2>
        <p>
          Lorem ipsum dolor sit amet, consectetur adipisicing elit. Aliquid
          distinctio molestias saepe quibusdam enim iste assumenda ea incidunt
          tempore sequi odit eius, ducimus nostrum quo corrupti autem,
          doloremque repellat maiores.
        </p>
      </article>
    </div>
    <div class="opinion-section">
      <section class="opinions">
        <p class="opinion">
          "Pregunta frecuente 1" <br /><br />
          <span class="answer"
            >Respuesta de la empresa al cliente para la pregunta de
            arriba...</span
          >
        </p>
        <p class="opinion">
          "Pregunta frecuente 2"<br /><br />
          <span class="answer"
            >Respuesta de la empresa al cliente para la pregunta de
            arriba...</span
          >
        </p>
        <p class="opinion">
          "Pregunta frecuente 3"<br /><br />
          <span class="answer"
            >Respuesta de la empresa al cliente para la pregunta de
            arriba...</span
          >
        </p>
        <p class="opinion">
          "Pregunta frecuente 4"<br /><br />
          <span class="answer"
            >Respuesta de la empresa al cliente para la pregunta de
            arriba...</span
          >
        </p>
        <p class="opinion">
          "Pregunta frecuente 5"<br /><br />
          <span class="answer"
            >Respuesta de la empresa al cliente para la pregunta de
            arriba...</span
          >
        </p>
        <p class="opinion">
          "Pregunta frecuente 6"<br /><br />
          <span class="answer"
            >Respuesta de la empresa al cliente para la pregunta de
            arriba...</span
          >
        </p>
        <p class="opinion">
          "Pregunta frecuente 7"<br /><br />
          <span class="answer"
            >Respuesta de la empresa al cliente para la pregunta de
            arriba...</span
          >
        </p>
        <p class="opinion">
          "Pregunta frecuente 8"<br /><br />
          <span class="answer"
            >Respuesta de la empresa al cliente para la pregunta de
            arriba...</span
          >
        </p>
        <p class="opinion">
          "Pregunta frecuente 9"<br /><br />
          <span class="answer"
            >Respuesta de la empresa al cliente para la pregunta de
            arriba...</span
          >
        </p>
      </section>
    </div>
    <Footer />
  </section>
</template>

<script>
import Footer from "./Footer.vue";

export default {
  name: "faq",
  components: {
    Footer,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
@import "../Style/Faq.css";
</style>