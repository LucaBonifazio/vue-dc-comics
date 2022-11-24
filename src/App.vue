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

</style>
