<template>
    <div class="cubes-container">
      <canvas id="canvas3d" ref="canvas3d"></canvas>
    </div>
  </template>
  
  <script>
  import { Application } from '@splinetool/runtime';
  
  export default {
    name: 'CubesModel',
    mounted() {
      const canvas = this.$refs.canvas3d;
      const app = new Application(canvas);
      app.load('https://prod.spline.design/waDHAOwNu-VDPzTt/scene.splinecode');
    }
  };
  </script>
  
  <style scoped>
  .cubes-container {
    width: 100vw;
    height: 100vh;
  }
  
  #canvas3d {
    width: 100vw;
    height: 100vh;
  }
  </style>