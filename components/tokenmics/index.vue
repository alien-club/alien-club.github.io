<template>
  <div class="center-bot-page">
    <div class="center-bot-page-project">
      <div class="center-bot-page-project-info">
        <img src="../../assets/images/center/center-bot-star.png" alt="" />
        <p>
          The completed Alien Club ecosystem brings sustainable passive income
          flow to palyers or investor just simply by playing GAMES,
          staking/collecting NFT, and building Alien Castles, that’s what we
          entitle the neo“Play2Earn”Alien Club.
        </p>
      </div>
      <div class="center-bot-page-project-info">
        <img src="../../assets/images/center/center-bot-star.png" alt="" />
        <p>
          NFT Games go virus in cyrpto world and expand way beyond our
          expectation. Aliens, Items, Castles, tokens are literally your own
          irreplaceable assets.
        </p>
      </div>
      <div class="center-bot-page-project-info">
        <img src="../../assets/images/center/center-bot-star.png" alt="" />
        <p>
          The limited Alien types would be invaluable and symbolize the great
          potential for revaluation.
        </p>
      </div>
    </div>
    <Echart />
  </div>
</template>

<script>
import Echart from "./echart.vue";
export default {
  components: {
    Echart,
  },
};
</script>

<style lang='scss' scoped>
.center-bot-page {
  min-width: 1200px;
  height: 1794px;
  background-image: url("../../assets/images/center/center-bot-bg.png");
  background-repeat: no-repeat;
  background-size: auto 100%;
  background-position: center center;
  background-color: #647241;
}
.center-bot-page-project {
  width: 1180px;
  margin: 0 auto;
  display: flex;
  flex-direction: column;
  align-items: center;
  padding-top: 386px;
  &-info {
    display: flex;
    align-items: center;
    height: 108px;
    margin: 10px 0;
    img {
      width: 64px;
      height: 88px;
    }
    p {
      margin-left: 77px;
      width: 900px;
      font-size: 24px;
      font-family: STSongti-SC-Regular, STSongti-SC;
      font-weight: 400;
      color: #eaffb5;
      line-height: 36px;
    }
  }
}
</style>