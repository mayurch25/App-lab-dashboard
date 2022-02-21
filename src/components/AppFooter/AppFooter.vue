<template>
  <div class="footer-section">
    <div style="text-align: center">
      <span class="app-logo-text">App</span>
      <span class="lab-logo-text">Lab</span>
    </div>
    <div class="footer-contents">
      <div class="custom-nav-text">Home</div>
      <div class="custom-nav-text">Key Features</div>
      <div class="custom-nav-text">Pricing</div>
      <div class="custom-nav-text">Testiminial</div>
      <div class="custom-nav-text">FAQ</div>
    </div>
    <div class="social-icon">
      <img
        src="../../assets/social-icon/Assetinstagram.png"
        alt=""
        class="icon-social"
      />
      <img
        src="../../assets/social-icon/assetFb.png"
        alt=""
        class="icon-social"
      />
      <img
        src="../../assets/social-icon/assetTwittter.png"
        alt=""
        class="icon-social"
      />
    </div>
  </div>
</template>


<script>
export default {
  name: "footer-section",
  mixins: [],
  data() {
    return {};
  },

  methods: {},
};
</script>

<style scoped>
</style>

<style lang="scss" scoped>
@import url("./AppFooter.css");

.social-icon {
  .icon-social {
    margin: 40px 20px;
    width: 23px;
    height: 23px;
  }
}
</style>