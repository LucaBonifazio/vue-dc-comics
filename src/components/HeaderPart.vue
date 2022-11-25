<template>
  <div class="bg_container">
    <div class="navbar container">
      <a href="@!"><img src="@/components/img/dc-logo.png" alt="logo"></a>
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
  </div>
</template>

<script>
export default {
  name: 'HeaderPart',
};
</script>

<style lang="scss" scoped>
.navbar {
  display: flex;
  align-items: center;
  justify-content: space-between;
  height: 100px;
}

img {
  width: 70px;
  height: 70px;
  cursor: pointer;
  &:hover {
    transform: scale(1.2);
    transform: rotate(-45deg);
    transition: transform 0.5s ease-in-out;
  }
}
.navbar_list {
  display: flex;
  justify-content: center;
  align-items: center;
  flex-wrap: wrap;
  gap: 1rem;
  height: 100%;
  a {
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100%;
  color: rgb(0, 0, 0);
  &:hover{
    color:  #0282F9;
    background-color: rgb(207, 235, 253);
  }
  }
}

</style>
