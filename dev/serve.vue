<script>
import Vue from 'vue';
// Uncomment import and local "components" registration if library is not registered globally.
// import { VueWeatherSample } from '@/entry.esm';

export default Vue.extend({
  name: 'ServeDev',
  // components: {
  //  VueWeatherSample,
  // }
});
</script>

<template>
  <div id="app">
    <vue-weather-sample />
  </div>
</template>
