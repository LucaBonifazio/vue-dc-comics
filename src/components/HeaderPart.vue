<template>
  <div class="bg_container">
    <div class="navbar container">
      <a href="#!"> <img src="@/components/img/dc-logo.png" alt="logo" /></a>
      <div class="navbar_list">
        <ul>
          <li v-for="item in listItems" :key="item.text"><a href="#!">{{item.text}}</a></li>
        </ul>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HeaderPart',
  data() {
    return {
      listItems: [
        {
          url: '#COMICS',
          text: 'COMICS',
        },
        {
          url: '#MOVIES',
          text: 'MOVIES',
        },
        {
          url: '#TV',
          text: 'TV',
        },
        {
          url: '#GAMES',
          text: 'GAMES',
        },
        {
          url: '#COLLECTIBLES',
          text: 'COLLECTIBLES',
        },
        {
          url: '#VIDEOS',
          text: 'VIDEOS',
        },
        {
          url: '#FANS',
          text: 'FANS',
        },
        {
          url: '#NEWS',
          text: 'NEWS',
        },
        {
          url: '#SHOP',
          text: 'SHOP',
        },
      ],
    };
  },
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
  ul {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100%;
    color: rgb(0, 0, 0);
    li{
      display: flex;
      justify-content: center;
      align-items: center;
      padding: 0 .3em;
      height: 100%;
      a{
        display: flex;
        justify-content: center;
        align-items: center;
        height: 100%;
        color: #000000;
        &:hover {
          color: rgb(0, 157, 255);
          background-color: rgb(207, 235, 253);
        }
      }
    }
  }
}
</style>
