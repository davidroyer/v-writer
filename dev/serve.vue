<script>
import Vue from 'vue';
// Uncomment import and local "components" registration if library is not registered globally.
// import { VWriterSample } from '@/entry.esm';

export default Vue.extend({
  name: 'ServeDev',
  // components: {
  //  VWriterSample,
  // }
});
</script>

<template>
  <div id="app">
    <v-editor/>
  </div>
</template>
