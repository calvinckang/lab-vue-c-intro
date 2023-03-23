<script setup>
import NavBar from "./components/NavBar.vue";
</script>

<template>
  <NavBar />
  <main>
    <section class="header-logo">
      <img src="./assets/logo.svg" alt="Vue Logo" />
      <h1>Welcome to Vue.js</h1>
      <h5>Become a coding ninja with the fastest-growing JavaScript framework</h5>
      <button>Awesome!</button>
    </section>
  </main>
</template>

<style scoped>
.header-logo {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
}
.header-logo img {
  width: 129px;
  height: 129px;
}
</style>