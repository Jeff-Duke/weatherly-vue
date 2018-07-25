<template>
  <div id="app">
    <h1>{{this.WeatherData.current_observation.display_location.full}}</h1>
  </div>
</template>

<script>
import WeatherData from './WeatherData'
export default {
  name: 'app',
  data() {
      return {
        WeatherData
      }
    },
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
