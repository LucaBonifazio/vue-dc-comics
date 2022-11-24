<template>
  <div>
    <HeaderPart />
    <MainPart />
    <FooterPartIcon />
    <FooterPartLink />
    <FooterPartSocial />
  </div>
</template>

<script>
import HeaderPart from '@/components/HeaderPart.vue';
import MainPart from '@/components/MainPart.vue';
import FooterPartIcon from '@/components/FooterPartIcon.vue';
import FooterPartLink from '@/components/FooterPartLink.vue';
import FooterPartSocial from '@/components/FooterPartSocial.vue';

export default {
  components: {
    HeaderPart,
    MainPart,
    FooterPartIcon,
    FooterPartLink,
    FooterPartSocial,
  },
};
</script>

<style lang="scss">
  *{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
  }

  body {
    height: 100vh;
  }

  .container {
    display: flex;
    max-width: 80%;
    height: 100%;
    margin: auto;
  }

  li {
    list-style: none;
  }

  a {
    text-decoration: none;
  }
</style>
