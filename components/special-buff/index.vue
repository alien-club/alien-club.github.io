<template>
  <div class="center-top-page">
    <div class="center-top-page-logo">
      <a href="#"></a>
    </div>
    <div class="center-top-page-title">
      <img src="../../assets/images/center/center-top-title.png" alt="" />
    </div>
    <div class="center-top-page-title-info">
      Holding ALIEN tokens and building your own army to earn the EYE tokens
      which can be used to buy energy from the Alien game. The EYE is a special
      token which can be used to buff your Characters to get levels up in the
      battle as well as to be the key factors to forge more materials for your
      virtual castles.
    </div>
    <h3 class="center-top-page-title-nft">
      <img src="../../assets/images/center/center-top-title-nft.png" alt="" />
    </h3>
    <div class="center-top-page-nft-wrap">
      <h3>Included with each combination are 4 types of gear items:</h3>
      <div class="center-top-page-card-wrap"></div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style lang='scss' scoped>
.center-top-page {
  min-width: 1200px;
  height: 1867px;
  background-image: url("../../assets/images/center/center-top-bg.png");
  background-repeat: no-repeat;
  background-size: auto 100%;
  background-position: center center;
  background-color: #000;
}
.center-top-page-logo {
  display: flex;
  justify-content: center;
  > a {
    display: inline-block;
    width: 520px;
    height: 200px;
    background-image: url("../../assets/images/center/center-top-logo.png");
    background-repeat: no-repeat;
    background-size: 100% 100%;
    margin: 142px auto 0;
  }
}
.center-top-page-title {
  width: 221px;
  height: 37px;
  margin: 40px auto 0;
  img {
    width: 100%;
    height: 100%;
  }
}
.center-top-page-title-info {
  margin: 33px auto 0;
  text-align: center;
  width: 1180px;
  height: 99px;
  font-size: 24px;
  font-family: HoeflerText-Regular;
  font-weight: 400;
  color: #a0afbe;
  line-height: 33px;
}
.center-top-page-title-nft {
  width: 524px;
  height: 37px;
  margin: 96px auto 0;
  img {
    width: 100%;
    height: 100%;
  }
}
.center-top-page-nft-wrap {
  width: 1180px;
  margin: 0 auto;
  > h3 {
    height: 33px;
    font-size: 24px;
    font-family: HoeflerText-Regular;
    font-weight: 400;
    color: #a0afbe;
    line-height: 33px;
  }
  .center-top-page-card-wrap {
  }
}
</style>