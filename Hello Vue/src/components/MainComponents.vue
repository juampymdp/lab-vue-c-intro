<script setup>
</script>

<template>
  <main>
    <img class="center-img" src="../images/vue_logo.png" alt="Vue.js Logo" />
    <h1 class="titulo">Welcome to Vue.js</h1>
    <p class="texto">Become a coding ninja with the fastest-growing JavaScript framework</p>
    <button class="awesome-btn">Awesome!</button>
  </main>
</template>

<style scoped>
main {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  margin-top: 50px;
  margin-bottom: 50px;
  font-family:
    system-ui,
    -apple-system,
    BlinkMacSystemFont,
    'Segoe UI',
    Roboto,
    Oxygen,
    Ubuntu,
    Cantarell,
    'Open Sans',
    'Helvetica Neue',
    sans-serif;
}

.center-img {
  width: 120px;
  height: 120px;
}

.titulo {
  color: #2b2f30;
  font-size: 50px;
  margin: 20px 0;
  text-align: center;
  font-weight: bold;
}

.texto {
  font-size: 1.2em;
  font-weight: bold;
  text-align: center;
}

.awesome-btn {
  background-color: gray;
  color: white;
  font-size: 1.2em;
  padding: 10px 20px;
  border: none;
  border-radius: 15px;
  cursor: pointer;
  margin-top: 20px;
}

.awesome-btn:hover {
  background-color: darkgray;
}
</style>