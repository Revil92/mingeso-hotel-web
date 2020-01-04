<template>
  <div id="app">
    <div id="nav" class="nav-bar mb-3">
      <router-link to="/">Inicio</router-link>
      <span> | </span>
      <router-link to="/clients/create">Crear Cliente</router-link>
      <span> | </span>
      <router-link to="/booking/create">Crear Reserva</router-link>
      <span> | </span>
      <router-link to="/checking/create">Check In</router-link>
      <span> | </span>
      <router-link to="/checkout/create">Check Out</router-link>
    </div>
    <router-view />
  </div>
</template>

<style lang="scss">
@import "assets/scss/app";

.nav-bar {
  border-bottom: 1px solid gray;
}
</style>
