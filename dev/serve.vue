<script>
import Vue from 'vue';
// Uncomment import and local "components" registration if library is not registered globally.
import { VueWeatherUI } from '@/entry.esm';

export default Vue.extend({
  name: 'ServeDev',
  components: {
   VueWeatherUI,
  }
});
</script>

<template>
  <div id="app">
    <vue-weather-UI />
  </div>
</template>
