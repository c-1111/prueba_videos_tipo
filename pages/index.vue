<template>
    <div class="video-wrapper">
  <video autoplay muted loop playsinline preload="metadata">
	  <source src="/vid/cartel_a2_disual_1.mp4" type="video/mp4">
  </video>
</div>

</template>

<style>
html {
  box-sizing: border-box;
  height: 100%;
}
*, *:before, *:after {
  box-sizing: inherit;
}
body {
  height: 100%;
  margin: 0;
}
.video-wrapper {
  width:100%;
  height:100vh;
  overflow: hidden;
  
  video {
    object-fit: cover;
    width:100%;
    height:100%;
  }
}
</style>