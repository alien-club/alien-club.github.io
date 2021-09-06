<template>
  <div class="header">
    <a class="header-logo" href="#"></a>
    <div class="header-link">
      <nuxt-link to="#" class="header-link-home">Home</nuxt-link>
      <nuxt-link to="#" class="header-link-roadmap">Roadmap</nuxt-link>
      <nuxt-link to="#" class="header-link-moni">MONI</nuxt-link>
      <nuxt-link to="#" class="header-link-marketplace">Marketplace</nuxt-link>
      <nuxt-link to="#" class="header-link-doc">Doc</nuxt-link>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style lang='scss' scoped>
.header {
  display: flex;
  justify-content: center;
  align-items: center;
}
.header-logo {
  display: inline-block;
  width: 194px;
  height: 90px;
  background: url("../../assets/images/header/header-logo.png");
  background-repeat: no-repeat;
  background-size: 100% 100%;
  margin-right: 35px;
}
.header-link {
  > a {
    display: inline-block;
    width: 108px;
    height: 56px;
    background: url("../../assets/images/header/header-btn-bg.png");
    background-repeat: no-repeat;
    background-size: 100% 100%;
    font-size: 16px;
    font-family: PingFangSC-Semibold, PingFang SC;
    font-weight: 600;
    color: #ffffff;
    line-height: 45px;
    text-align: center;
    margin: 0 15px;
  }
}
</style>