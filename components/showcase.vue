<template>
  <a :href="url" target="_blank">
    <div class="p-4">
      <div class="flex justify-center items-center h-80 rounded-xl shadow-xl">
        <slot />
      </div>
    </div>
  </a>
</template>

<script lang="ts">
import Vue from 'vue'

export default Vue.extend({
  props: {
    url: String
  }
})
</script>
