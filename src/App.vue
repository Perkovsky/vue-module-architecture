<template>
  <img alt="Vue logo" src="./assets/logo.png" />
  <mg-amenity-list />
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import MgAmenityList from './modules/Amenity/components/AmenityList.vue'

export default defineComponent({
  name: 'App',
  components: {
    MgAmenityList
  }
})
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>