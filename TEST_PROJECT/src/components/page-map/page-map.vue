<template>
    <div id="map" class="map"></div>
</template>

<script async defer
 setup lang="ts"
 src="https://maps.googleapis.com/maps/api/js?key=AIzaSyDDiCLXghb5ALx0FvTuHTw40dO2hn5f3_8&callback=initMap">
</script>

<style scoped>
  .map {
    width: 100vw;
    height: 100vh;
  }
</style>