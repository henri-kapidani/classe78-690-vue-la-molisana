<template>
  <header>
    <img
      src="@/img/la-molisana-logo.png"
      alt=""
    >
    <nav>
      <ul>
        <li
          v-for="eleMenu in arrMenu"
          :key="eleMenu.text"
        >
          <a :href="eleMenu.url">{{ eleMenu.text }}</a>
        </li>
      </ul>
    </nav>
  </header>
</template>

<script>
export default {
  name: 'HeaderPage',
  data() {
    return {
      arrMenu: [
        {
          url: '#home',
          text: 'Home',
        },
        {
          url: '#Prodotti',
          text: 'Prodotti',
        },
        {
          url: '#Chi-siamo',
          text: 'Chi siamo',
        },
        {
          url: '#Contatti',
          text: 'Contatti',
        },
      ],
    };
  },
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
