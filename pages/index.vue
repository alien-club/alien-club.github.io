<template>
  <div class="home-page">
    <div class="header-page">
      <Header />
      <div class="header-page_center">
        <img src="../assets/images/header/header-center-bg.png" alt="" />
        <p>
          Our ecosystem including: Alien Game play, Alien Club and Alien
          Staking. We want to create a METAVERSE of lovely Aliens where players
          can play games to earn, staking/collecting NFTs to earn, as well as
          grow their own in-game characters into the virtual Lands and Castles.
        </p>
        <a href="">white paper</a>
      </div>
    </div>
    <div class="center-page">
      <CenterTop />
      <CenterBot />
    </div>
  </div>
</template>

<script>
import Header from "../components/header/index.vue";
import CenterTop from "../components/special-buff/index.vue";
import CenterBot from "../components/tokenmics/index.vue";
export default {
  components: {
    Header,
    CenterTop,
    CenterBot,
  },
};
</script>
<style lang='scss' scoped>
.header-page {
  min-width: 1200px;
  height: 1200px;
  background: url("../assets/images/header/header-bg.png");
  background-repeat: no-repeat;
  background-size: auto 100%;
  background-position: center center;
  background-color: #51392f;
}
.header-page_center {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  margin-top: 288px;
  > img {
    width: 935px;
    height: 533px;
  }
  > p {
    width: 1080px;
    height: 108px;
    font-size: 24px;
    font-family: HoeflerText-Regular;
    font-weight: 400;
    color: #ecb28d;
    line-height: 36px;
    margin-top: 16px;
    text-align: center;
  }
  > a {
    margin-top: 28px;
    display: inline-block;
    width: 220px;
    height: 70px;
    background: url("../assets/images/header/header-btn-big-bg.png");
    background-repeat: no-repeat;
    background-size: 100% 100%;
    font-size: 24px;
    font-family: HoeflerText-Regular;
    color: #ecb28d;
    line-height: 55px;
    text-align: center;
  }
}
</style>
