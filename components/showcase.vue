<template>
  <a :href="'https://github.com/lilisako/copy-paste-tailwind/blob/main/components/' + url" target="_blank">
    <div class="p-4">
      <div class="flex relative justify-center items-center h-80 rounded-xl shadow-xl">
        <div class="absolute top-8 left-4">
          <p class="font-bold text-gray-200">#{{ hashtag }}</p>
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
