<template>
  <div id="app">
    <parent />
  </div>
</template>

<script lang="ts">
import Vue from "vue";
import Parent from './Parent.vue'

export default Vue.extend({
  name: "App",
  components: {
    Parent
  }
});
</script>
