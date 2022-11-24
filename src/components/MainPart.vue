<template>
  <div class="bg_container">
    <div class="main_content container">
      <a href="#!">Content goes here</a>
    </div>
  </div>
</template>

<script>
export default {
  name: 'MainPart',
};
</script>

<style lang="scss" scoped>
.bg_container{
  background-color: black;
}
.main_content {
  display: flex;
  justify-content: center;
  text-align: center;
  height: 677px;
}
a {
  color: white;
}

</style>
