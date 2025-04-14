<template>
  <div class="spline-container">
    <canvas id="canvas3d"></canvas>
  </div>
</template>

<script>
import { Application } from '@splinetool/runtime';

export default {
  name: 'SplineModel',
  mounted() {
    const canvas = document.getElementById('canvas3d');
    const app = new Application(canvas);
    app.load('https://prod.spline.design/5U4e8UODlxThiGoT/scene.splinecode');
  },
};
</script>

<style scoped>
.spline-container {
  width: 100vw;
  height: 100vh;
}

</style>