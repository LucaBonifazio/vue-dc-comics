<template>
  <div class="bg_container">
    <div class="navbar_down container">
      <a href="#!">
        <img src="@/components/img/buy-comics-digital-comics.png" alt="icon">
        DIGITAL COMICS
      </a>
      <a href="#!">
        <img src="@/components/img/buy-comics-merchandise.png" alt="icon">
        DC MERCHANDISE
      </a>
      <a href="#!">
        <img src="@/components/img/buy-comics-subscriptions.png" alt="icon">
        SUBSCRIPTION
      </a>
      <a href="#!">
        <img src="@/components/img/buy-comics-shop-locator.png" alt="icon">
        COMIC SHOP LOCATOR
      </a>
      <a href="#!">
        <img src="@/components/img/buy-dc-power-visa.svg" alt="icon">
        DC POWER VISA
      </a>
    </div>
  </div>
</template>

<script>
export default {
  name: 'FooterPartIcon',
};
</script>

<style lang="scss" scoped>
  .bg_container{
    background-color: rgb(45, 124, 241);
  }
  .navbar_down{
    display: flex;
    justify-content: space-around;
    align-items: center;
    width: 100%;
    height: 130px;
    padding: 1em;
  }

  a{
    display: flex;
    justify-content: center;
    align-items: center;
    width: 100%;
    height: 100%;
    font-size: .7em;
    color: #fff;
    &:hover {
      transform: scale(1.1);
      transition: transform 0.2s ease-in-out;
    }
  }

  img {
    width: 50px;
    margin-right: .5em;
  }
</style>
