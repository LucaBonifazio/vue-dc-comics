<template>
  <div class="bg_container">
    <section class="slider_image"></section>
    <section class="cards_box">
      <div class="card_box"></div>
    </section>
  </div>
</template>

<script>
// import MainCard from '@/components/MainCard.vue';

export default {
  name: 'MainPart',
};
</script>

<style lang="scss" scoped>
.bg_container {
  background-color: black;
}
.slider_image {
  display: flex;
  justify-content: center;
  text-align: center;
  height: 300px;
  background-image: url('@/components/img/jumbotron.jpg');
  object-position: center;
  background-size: cover;
  background-repeat: no-repeat;
}
.cards_box {
  display: flex;
  justify-content: center;
  text-align: center;
  height: 677px;
}
</style>
