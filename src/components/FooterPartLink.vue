<template>
  <div class="bg_container">
    <div class="link_container container">
      <div class="link_list_box">
        <h3>DC COMICS</h3>
        <ul class="list">
          <li>
            <a href="#!">Characters</a>
          </li>
          <li>
            <a href="#!">Comics</a>
          </li>
          <li>
            <a href="#!">Movies</a>
          </li>
          <li>
            <a href="#!">TV</a>
          </li>
          <li>
            <a href="#!">Games</a>
          </li>
          <li>
            <a href="#!">Videos</a>
          </li>
          <li>
            <a href="#!">News</a>
          </li>
        </ul>
        <h3>SHOP</h3>
        <ul class="list">
          <li>
            <a href="#!">Shop DC</a>
          </li>
          <li>
            <a href="#!">Shop DC Collectibles</a>
          </li>
        </ul>
        <h3>DC</h3>
        <ul class="list">
          <li>
            <a href="#!">Terms Of Use</a>
          </li>
          <li>
            <a href="#!">Privacy policy (New)</a>
          </li>
          <li>
            <a href="#!">Ad Choises</a>
          </li>
          <li>
            <a href="#!">Advertising</a>
          </li>
          <li>
            <a href="#!">Jobs</a>
          </li>
          <li>
            <a href="#!">Subscriptions</a>
          </li>
          <li>
            <a href="#!">Talent Workshops</a>
          </li>
          <li>
            <a href="#!">CPSC Certificates</a>
          </li>
          <li>
            <a href="#!">Ratings</a>
          </li>
          <li>
            <a href="#!">Shop Help</a>
          </li>
          <li>
            <a href="#!">Contact Us</a>
          </li>
        </ul>
        <h3>SITES</h3>
        <ul class="list">
          <li>
            <a href="#!">DC</a>
          </li>
          <li>
            <a href="#!">MAD Magazine</a>
          </li>
          <li>
            <a href="#!">DC Kids</a>
          </li>
          <li>
            <a href="#!">DC Universe</a>
          </li>
          <li>
            <a href="#!">DC Power Visa</a>
          </li>
        </ul>
      </div>
      <div class="image_box">
        <img src="@/components/img/dc-logo-bg.png" alt="logo" />
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'FooterPartLink',
};
</script>

<style lang="scss" scoped>
.bg_container {
  background-image: url(@/components/img/footer-bg.jpg);
  object-fit: contain;
  object-position: center;
}
.link_container {
  display: flex;
  align-items: center;
  justify-content: space-between;
  width: 100%;
  height: 300px;
  padding: 1rem;
  color: rgb(255, 255, 255);
}
.link_list_box {
  display: flex;
  flex-direction: column;
  flex-wrap: wrap;
  height: 100%;
}

ul {
  margin-bottom: 1.8em;
  margin-right: 1.5em;
}

a {
  color: rgb(136, 136, 136);
  font-size: 12px;
  &:hover {
    color: white;
  }
}

img {
  width: 350px;
  height: 350px;
  object-fit: contain;
  object-position: center;
  &:hover {
    transform: scale(1.1);
  }
}
</style>
