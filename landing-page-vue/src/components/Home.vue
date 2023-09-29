<template>
  <div>
    <div class="home">
      <main class="Main">
        <div class="MainTitle">
          <h1>Avanzando hacia el futuro</h1>
        </div>
        <article class="Description">
          <p>
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Obcaecati,
            consequuntur asperiores pariatur iure illum quasi enim placeat
            neque, similique voluptatibus autem ab at quisquam, debitis deserunt
            ipsam labore corporis soluta!
          </p>
        </article>
        <div class="btnServicios">
          <button class="boton">Nuestros servicios</button>
        </div>
      </main>
    </div>
    <section class="SectionMain">
      <div class="SectionMain-div1">
        <div class="imgContainer">
          <img src="../../resources/check-circle-solid.png" alt="" />
        </div>
        <div class="sectionText1">
          <p>
            Ofrecemos servicos para todo tipo de empresa, comercio y/o
            emprendimiento.
          </p>
        </div>
        <div class="sectionText2">
          <p>
            Lorem ipsum, dolor sit amet consectetur adipisicing elit. Eos,
            saepe. Velit dicta incidunt.
          </p>
        </div>
      </div>
      <div class="SectionMain-div2">
        <div class="Opiniones">
          <p>
            “Opinion de cliente referente a nuestros servicios 1”<br /><br /><span
              class="usuario"
              >-Juan Juanin</span
            >
          </p>
        </div>
        <div class="Opiniones">
          <p>
            “Opinion de cliente referente a nuestros servicios 2”<br /><br /><span
              class="usuario"
              >-Juana Juanina</span
            >
          </p>
        </div>
        <div class="Opiniones">
          <p>
            “Opinion de cliente referente a nuestros servicios 3”<br /><br /><span
              class="usuario"
              >-George de la Selva</span
            >
          </p>
        </div>
      </div>
    </section>
  </div>
</template>

<script>
export default {
  name: "home",
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
@import "../Style/Home.css";
</style>
