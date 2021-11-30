<template>
  <GmapMap
    style="width: 100%; height: 100%; position: absolute; top: 0; bottom: 0"
    :center="{ lat: 35, lng: 139 }"
    :zoom="14"
    :options="{
      streetViewControl: false,
      fullscreenControl: false,
      clickable: false,
      minZoom: 12,
      maxZoom: 21,
      gestureHandling: 'greedy',
      clickableIcons: false,
      scaleControl: true,
    }"
  >
  </GmapMap>
</template>

<script>
export default {
  async mounted() {},
};
</script>
