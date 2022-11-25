<template>
  <div class="card">
    <div class="contents">
      <img
        :src="card.thumb"
        :alt="card.series"
      >
      <h2>{{ card.series}}</h2>
    </div>
  </div>
</template>

<script>
export default {
  name: 'MainCard',
  props: {
    card: Object,
  },
};
</script>

<style lang="scss" scoped>
  .card {
    text-align: center;
    padding: .1rem;
    .contents {
      padding: 1em;
      height: 100%;
      h2 {
        color: white;
        font-size: 1.2rem;
      }
      &:hover {
        transform: scale(1.1);
      }
    }
  }
</style>
