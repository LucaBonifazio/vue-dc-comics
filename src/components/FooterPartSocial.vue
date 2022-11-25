<template>
  <div class="bg_container">
    <div class="footer_social container">
      <div class="btn"><a>SIGN-UP NOW!</a></div>
      <div class="social_box">
        <div class="follow_link">FOLLOW US</div>
        <div class="social_icon">
          <img src="@/components/img/footer-facebook.png" alt="social">
          <img src="@/components/img/footer-twitter.png" alt="social">
          <img src="@/components/img/footer-youtube.png" alt="social">
          <img src="@/components/img/footer-pinterest.png" alt="social">
          <img src="@/components/img/footer-periscope.png" alt="social">
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'FooterPartSocial',
};
</script>

<style lang="scss" scoped>
.bg_container {
  position: relative;
  z-index: 10;
  height: 100px;
  background-color: rgb(61, 61, 61);
}
.footer_social {
  display: flex;
  justify-content: space-between;
  align-items: center;
}
.btn {
  display: flex;
  align-items: center;
  justify-content: center;
  width: 150px;
  height: 40px;
  border: 3px solid rgb(0, 143, 179);
  color: white;
  cursor: pointer;
  &:hover {
    transform: scale(1.2);
    background-color: rgb(206, 206, 206);
    color: black;
  }
}

.social_box{
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 1em;
  gap: 1em;
}
.follow_link{
  color:  #0282F9;
  font-size: 15px;
  font-weight: bold;
  &:hover {
    transform: scale(1.2);
  }
}

.social_icon{
  display: flex;
  gap: 1em;
  img{
    &:hover {
    transform: scale(1.2);
    }
  }
}
</style>
