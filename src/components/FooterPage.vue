<template>
  <footer>
    <a
      class="logo"
      href="/"
    >
      <img
        src="@/img/la-molisana-logo.png"
        alt="La molisana"
      >
    </a>

    <nav>
      <ul class="footer-links">
        <li>
          <h4>Pastificio</h4>
          <ul>
            <li><a href="#!">Il Pastificio</a></li>
            <li><a href="#!">Grano</a></li>
            <li><a href="#!">Filiera</a></li>
            <li><a href="#!">100 anni di pasta</a></li>
            <li><a href="#!">Sartoria della pasta</a></li>
          </ul>
        </li>

        <li>
          <h4>Prodotti</h4>
          <ul>
            <li><a href="#!">Le classiche</a></li>
            <li><a href="#!">Le Integrali</a></li>
            <li><a href="#!">Le Speciali</a></li>
            <li><a href="#!">Le Biologiche</a></li>
            <li><a href="#!">Le Gluten-free</a></li>
          </ul>
        </li>
      </ul>
    </nav>

    <img
      class="footer-mountains"
      src="@/img/footer-montagne-bottom.jpg"
      alt="Mountains"
    >
  </footer>
</template>

<script>
export default {
  name: 'FooterPage',
};
</script>

<style lang="scss" scoped>
footer {
  display: flex;
  justify-content: center;
  flex-wrap: wrap;
  gap: 2rem;
  margin-top: 4rem;
  // max-width: v-bind(size);

  ul {
    list-style: none;
  }

  .footer-links {
    display: flex;
    gap: 3rem;
  }

  .footer-mountains {
    flex: 0 0 100%;
    min-width: 0;
  }
}
</style>
