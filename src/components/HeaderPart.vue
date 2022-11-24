<template>
  <div class="navbar container">
    <img src="@/components/img/dc-logo.png" alt="logo">
    <div class="navbar_list">
      <a href="#!">CHARACTERS</a>
      <a href="#!">COMICS</a>
      <a href="#!">MOVIES</a>
      <a href="#!">TV</a>
      <a href="#!">GAMES</a>
      <a href="#!">COLLECTIBLES</a>
      <a href="#!">VIDEOS</a>
      <a href="#!">FANS</a>
      <a href="#!">NEWS</a>
      <a href="#!">SHOP</a>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HeaderPart',
};
</script>

<style lang="scss" scoped>
  a {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100%;
    color: rgb(0, 0, 0);
    &:hover{
      color: rgb(0, 132, 255);
      background-color: rgb(207, 235, 253);
    }
  }
  .navbar {
    display: flex;
    align-items: center;
    justify-content: space-between;
    height: 100px;
  }

  img {
    width: 70px;
    height: 70px;
  }
  .navbar_list {
    display: flex;
    justify-content: center;
    align-items: center;
    flex-wrap: wrap;
    gap: 1rem;
    height: 100%;
  }

</style>
