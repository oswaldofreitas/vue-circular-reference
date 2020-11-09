<template>
  <div class="Child">

  </div>
</template>

<script lang="ts">
import { defineComponent } from '@vue/composition-api';
import Parent from './Parent.vue'

export default defineComponent({
  name: 'Child',
  components: {
    Parent
  }
});
</script>
