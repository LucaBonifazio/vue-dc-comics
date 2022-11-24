<template>
  <div class="footer_social container">
    <div class="btn">SIGN-UP NOW!</div>
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
</template>

<script>
export default {
  name: 'FooterPartSocial',
};
</script>

<style lang="scss" scoped>
.footer_social {
  display: flex;
  justify-content: space-between;
  position: relative;
  z-index: 10;
  background-color: rgb(61, 61, 61);
}
.btn {
  display: flex;
  align-items: center;
  justify-content: center;
  border: 3px solid rgb(0, 143, 179);
  color: white;
}

.social_box{
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 1em;
  gap: 1em;
}
.follow_link{
  color: rgb(0, 145, 230);
  font-size: 15px;
  font-weight: bold;
}

.social_icon{
  display: flex;
  gap: 1em;
}
</style>
