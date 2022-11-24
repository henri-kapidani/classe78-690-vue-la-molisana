<template>
  <main>
    <div class="container">
      Il contenuto va qui
    </div>
  </main>
</template>

<script>
export default {
  name: 'MainPage',
};
</script>

<style lang="scss" scoped>
  main {
    padding: 6rem 0;

    background-image: url('@/img/fondo-pag-speciali.jpg');
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;

    .container {
      max-width: 600px;
      margin: 0 auto;
      padding: 0 1rem;
    }
  }
</style>
