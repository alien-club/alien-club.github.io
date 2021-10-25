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
    <div class="center-top-page-title-nft-buff">
      <div class="center-top-page-title-nft-buff-left">
        <h3>LOOT BASED BUFF</h3>
        <span>-- a "fair mint" lab</span>
        <p>
          With billions of possible BUFF combinations, each BUFF card has its
          own unique advantages! Only 10,000 Combination cards can be minted in
          total. To produce randomized scarcity, each item may be augmented by a
          prefix or suffix based on a hash of your card ID. become the best
          Alien trainer and defeat your enemies!
        </p>
      </div>
      <div class="center-top-page-title-nft-buff-right">
        <h3>Random Trait Attribution</h3>
        <p>
          Minting the Combination BUFF card will assign the owner a token ID,
          and trait attribution happens deterministically whenever NFT's
          tokenURI method is called. Trait randomization is random but
          deterministic. It uses a hashing function applied to concatenate the
          BUFF card ID and the type of the item. Each type of item has an array
          of options to pluck a random item from those arrays.This creates
          special scarcity properties for each of the items!
        </p>
      </div>
    </div>
    <div class="center-top-page-nft-card-wrap">
      <h3>Included with each combination are 4 types of gear items:</h3>
      <div class="center-top-page-nft-card-item">
        <div class="center-top-page-nft-card-item-info">
          <span> Weapons </span> <span> Chest Armor </span>
          <span> Head Armor </span> <span> Foot Armor </span>
        </div>
        <div class="center-top-page-nft-card-item-weapons nft-card-show">
          <span>Weapons</span>
        </div>
        <div class="center-top-page-nft-card-item-chest nft-card-show">
          <span>Chest Armor</span>
        </div>
        <div class="center-top-page-nft-card-item-head nft-card-show">
          <span>Head Armor</span>
        </div>
        <div class="center-top-page-nft-card-item-foot nft-card-show">
          <span>Foot Armor</span>
        </div>
      </div>
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
.center-top-page-title-nft-buff {
  width: 1180px;
  height: 576px;
  margin: 50px auto 0;
  display: flex;
  justify-content: space-between;
  > div {
    width: 520px;
    height: 100%;
    background-image: url("../../assets/images/center/center-top-text-bg.png");
    background-repeat: no-repeat;
    background-size: 100% 100%;
  }
  &-left {
    padding: 80px 30px 0;
    > h3 {
      font-size: 32px;
      font-family: HoeflerText-Regular;
      color: #ecb28d;
      line-height: 45px;
    }
    > span {
      margin-top: 4px;
      font-size: 28px;
      font-family: HoeflerText-Regular;
      color: #ecb28d;
      line-height: 40px;
    }
    > p {
      margin-top: 26px;
      font-size: 24px;
      font-family: HoeflerText-Regular;
      color: #ecb28d;
      line-height: 33px;
    }
  }
  &-right {
    padding: 80px 30px 0;
    > h3 {
      font-size: 32px;
      font-family: STSongti-SC-Regular, STSongti-SC;
      color: #ecb28d;
      line-height: 45px;
    }
    > p {
      font-size: 24px;
      font-family: STSongti-SC-Regular, STSongti-SC;
      color: #ecb28d;
      line-height: 33px;
    }
  }
}
.center-top-page-nft-card-wrap {
  width: 1180px;
  margin: 0 auto;
  > h3 {
    margin-top: 36px;
    height: 33px;
    font-size: 24px;
    font-family: HoeflerText-Regular;
    font-weight: 400;
    color: #a0afbe;
    line-height: 33px;
  }
  .center-top-page-nft-card-item {
    margin-top: 20px;
    width: 1180px;
    height: 360px;
    background: linear-gradient(
      154deg,
      rgba(255, 255, 255, 0.5) 0%,
      rgba(0, 0, 0, 0.5) 100%
    );
    box-shadow: 0px 0px 7px 0px rgba(240, 240, 240, 0.5);
    border: 1px solid #3c3c3c;
    display: flex;
    align-items: center;
    padding: 0 30px;
    &-info {
      width: 251px;
      height: 297px;
      background: #000000;
      display: flex;
      flex-direction: column;
      justify-content: center;
      > span {
        margin-left: 30px;
        font-size: 24px;
        font-family: STSongti-SC-Regular, STSongti-SC;
        font-weight: 400;
        color: #ffffff;
        line-height: 33px;
      }
    }
    .nft-card-show {
      width: 204px;
      height: 299px;
      background-repeat: no-repeat;
      background-size: 100% 100%;
      position: relative;
      > span {
        display: inline-block;
        width: 100%;
        font-size: 24px;
        font-family: STSongti-SC-Regular, STSongti-SC;
        font-weight: 900;
        color: #ffffff;
        line-height: 33px;
        position: absolute;
        bottom: 25px;
        text-align: center;
      }
    }
    &-weapons {
      background-image: url("../../assets/images/center/weapons.png");
      margin-left: 30px;
    }
    &-chest {
      background-image: url("../../assets/images/center/chest-armor.png");
      margin-left: 10px;
    }
    &-head {
      background-image: url("../../assets/images/center/head-armor.png");
      margin-left: 10px;
    }
    &-foot {
      background-image: url("../../assets/images/center/foot-armor.png");
      margin-left: 10px;
    }
  }
}
</style>