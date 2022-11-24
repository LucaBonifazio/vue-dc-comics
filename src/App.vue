<template>
  <div>
    <HeaderPart />
    <MainPart />
    <FooterPart />
  </div>
</template>

<script>
import HeaderPart from '@/components/HeaderPart.vue';
import MainPart from '@/components/MainPart.vue';
import FooterPart from '@/components/FooterPart.vue';

export default {
  components: {
    HeaderPart,
    MainPart,
    FooterPart,
  },
};
</script>

<style lang="scss">
  *{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
  }

  .container {
    display: flex;
    justify-content: center;
    align-items: center;
    max-width: 80%;
    height: 100%;
    margin: auto;
  }

  a {
    text-decoration: none;
  }
</style>
