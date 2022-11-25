<template>
  <div class="card">
    <div class="contents">
      <!-- <img
        :src="imgUrl"
        :alt="title"
      >
      <h2>{{ title + ' - Cottura: ' + minCottura }}</h2> -->

      <img
        :src="pasta.src"
        :alt="pasta.titolo"
      >
      <h2>{{ pasta.titolo + ' - Cottura: ' + pasta.cottura }}</h2>
    </div>
  </div>
</template>

<script>
export default {
  name: 'CardPasta',

  // props: {
  //   imgUrl: {
  //     type: String,
  //     required: true,
  //   },
  //   title: {
  //     type: String,
  //     required: false,
  //     default: 'Titolo di default',
  //   },
  //   minCottura: {
  //     type: Number,
  //     required: false,
  //     default: 10,
  //   },
  // },

  props: {
    pasta: Object,
  },
};
</script>

<style lang="scss" scoped>
  .card {
    text-align: center;
    padding: .1rem;
    .contents {
      background-color: white;
      padding: 1em;
      height: 100%;

      img {
        max-width: 90%;
      }

      h2 {
        font-size: 1.2rem;
      }
    }
  }
</style>
