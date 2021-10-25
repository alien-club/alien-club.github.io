<template>
  <div class="center-bot-page-project-echart">
    <canvas id="canvas" width="1180px" height="500px" ref="canvas"></canvas>
  </div>
</template>

<script>
export default {
  data() {
    return {
      TokenPer: [
        {
          name: "NFT Rewards",
          number: 0.1,
        },
      ],
    };
  },
  mounted() {
    this.draw();
  },
  methods: {
    draw() {
      let Canvas = this.$refs.canvas;
      const Context = Canvas.getContext("2d");
      const Angle = Math.PI * 2;
      Context.beginPath(590, 250);
      Context.arc(590, 250, 250, 0, Angle);
      Context.lineTo(590, 250);
      Context.stroke();
    },
  },
};
</script>

<style lang='scss' scoped>
.center-bot-page-project-echart {
  display: flex;
  flex-direction: column;
  align-items: center;
}
</style>