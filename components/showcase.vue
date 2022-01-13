<template>
  <a :href="url" target="_blank">
    <div class="p-4">
      <div class="flex justify-center items-center h-80 rounded-xl shadow-xl relative">
        <div class="absolute top-8 left-4">
          <p class="text-2xl font-bold text-gray-300">#{{ hashtag }}</p>
        </div>
        <slot />
      </div>
    </div>
  </a>
</template>

<script lang="ts">
import Vue from 'vue'

export default Vue.extend({
  props: {
    url: String,
    hashtag: String
  }
})
</script>
