<template>
  <div class="Parent">

  </div>
</template>

<script lang="ts">
import { defineComponent } from '@vue/composition-api';
import Child from './Child.vue'

export default defineComponent({
  name: 'Parent',
  components: {
    Child
  }
});
</script>
