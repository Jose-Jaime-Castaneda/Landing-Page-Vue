<template>
  <div id="app">
    <header class="header">
      <div class="empresa">
        <router-link to="/" class="logo">Mi compañia</router-link>
      </div>
      <nav class="navbar">
        <ul class="navbar-ul">
          <i class="navbar-item">
            <router-link to="/" class="navbar-link">Inicio</router-link>
          </i>
          <i class="navbar-item">
            <router-link to="/" class="navbar-link">Acerca de</router-link>
          </i>
          <i class="navbar-item">
            <router-link to="/faq" class="navbar-link">PyR</router-link>
          </i>
        </ul>
      </nav>
      <router-link class="toggle" to="/">
        <button class="btn-toggle">Contacto</button>
      </router-link>
      <img
        v-on:click="menuResponsive"
        class="barras"
        src="../resources/bars-solid.svg"
        alt="MyLogo"
      />
    </header>
    <router-view />
  </div>
</template>

<script>
export default {
  name: "App",
  methods: {
    menuResponsive() {
      console.log("Menu Responsivo");
    },
  },
};
</script>

<style>
@import "./Style/Navbar.css";

* {
  margin: 0;
  padding: 0;
}
</style>
