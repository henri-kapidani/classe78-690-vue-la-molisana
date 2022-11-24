<template>
  <header>
    <img src="@/img/la-molisana-logo.png" alt="">
    <nav>
      <ul>
        <li><a href="#!">Home</a></li>
        <li><a href="#!">Prodotti</a></li>
        <li><a href="#!">Chi siamo</a></li>
        <li><a href="#!">Contatti</a></li>
      </ul>
    </nav>
  </header>
</template>

<script>
export default {
  name: 'HeaderPage',
};
</script>

<style lang="scss" scoped>
  header {
    text-align: center;

    nav {
      height: 3rem;

      ul {
        display: flex;
        justify-content: center;
        height: 100%;
        list-style: none;

        a {
          display: flex;
          justify-content: center;
          align-items: center;
          padding: 0 .5rem;
          height: 100%;

          &:hover {
            background-color: aquamarine;
          }
        }
      }
    }
  }
</style>
