<template>
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
</template>

<script>
export default {
  name: 'FooterPartIcon',
};
</script>

<style lang="scss" scoped>
  .navbar_down{
    display: flex;
    justify-content: space-around;
    align-items: center;
    width: 100%;
    height: 130px;
    padding: 1em;
    background-color: #fff;
    background-color: rgb(45, 124, 241);
  }

  a{
    display: flex;
    justify-content: center;
    align-items: center;
    width: 100%;
    height: 100%;
    font-size: .7em;
    color: #fff;
  }

  img {
    width: 50px;
    margin-right: .5em;
  }
</style>
