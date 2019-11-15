<template>
  <div class="mapTest">
    <div>map test</div>
    <mapbox
      access-token="pk.eyJ1Ijoicm9zZWJ1ZDEzIiwiYSI6ImNrMnpwang1MzAwNnozY215ZHRyOWJ4ZGoifQ.vIxcuz8s18oM4zoIeWnGuA"
      :map-options="{
        style: 'mapbox://styles/mapbox/light-v9',
        center: [-96, 37.8],
        zoom: 3,
      }"
    />
    <!-- the access-token is generated from my Mapbox account --Kaijie -->
  </div>
</template>

<script>
import Mapbox from 'mapbox-gl-vue'
/* more map functions will be added later */
export default {
  components: { 
    Mapbox
  }
}
</script>

<style>
#map {
  width: 100%;
  height: 500px;
}
</style>
