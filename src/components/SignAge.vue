<template>
    <div id="animation-container"></div>
  </template>
  
  <script lang="js">
  import lottie from 'lottie-web';
  import animationData from '../assets/ship.json';
  
  export default {
    name: 'SigNage',
    mounted() {
      const animationContainer = document.getElementById('animation-container');
  
      lottie.loadAnimation({
        container: animationContainer,
        animationData,
        renderer: 'svg',
        loop: true,
        autoplay: true
      });
    }
  };
  </script>
  