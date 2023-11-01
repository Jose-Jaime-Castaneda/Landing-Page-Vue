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
        :src="menuVisible ? '../resources/xmark-solid.svg' : '../resources/bars-solid.svg'"
        alt="Menu-Responsive"
      />
    </header>
    <router-view />
    <!-- Div del menú responsivo -->
    <div class="menu-responsivo" v-show="menuVisible">
      <ul>
        <li><router-link to="/">Inicio</router-link></li>
        <li><router-link to="/">Acerca de</router-link></li>
        <li><router-link to="/faq">PyR</router-link></li>
        <router-link class="toggleR" to="/">
          <button class="btn-toggleR">Contacto</button>
        </router-link>
      </ul>
    </div>
  </div>
</template>

<script>
export default {
  name: "App",
  data() {
    return {
      menuVisible: false,
    };
  },
  methods: {
    menuResponsive() {
      this.menuVisible = !this.menuVisible;
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
