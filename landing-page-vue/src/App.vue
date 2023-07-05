<template>
  <div id="app">
    <nav class="navbar">
      <div class="empresa">
        <a href="" class="logo">Mi compañia</a>
      </div>
      <div class="menu-navbar">
        <ul class="navbar-ul">
          <i><a href="">Inicio</a></i>
          <i><a href="">Acerca de</a></i>
          <i><a href="">PYR</a></i>
          <i><a href="">Contacto</a></i>
        </ul>
      </div>
      <button class="navbar-toggle">azs</button>
    </nav>
    <router-view />
  </div>
</template>

<script>
export default {
  name: "App",
};
</script>

<style>
@import "./Style/Navbar.css";

* {
  margin: 0;
  padding: 0;
}
</style>
