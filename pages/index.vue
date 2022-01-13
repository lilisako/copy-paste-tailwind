<template class="h-screen">
  <div class="py-16 px-4 md:px-14">
  <!-- start header -->
    <div class="flex justify-between pl-4">
      <NuxtLink to="/">
        <div class="flex items-center">
          <span class="mx-1 text-4xl material-icons">send</span>
          <h1 class="text-3xl font-bold">
            Copy-Paste Tailwind
          </h1>
          <p class="mx-4 text-xs font-bold text-gray-400">
            Tailwindのデザインをコピペで完結
          </p>
        </div>
      </NuxtLink>
    </div>
    <!-- end header -->
  <div class="grid grid-cols-1 md:grid-cols-2">
    <!-- HTML box -->
    <div class="p-4">
      <div class="flex justify-center items-center h-80 rounded-xl shadow-xl">
        <RoundButton />
      </div>
    </div>
    <div class="p-4">
      <div class="flex justify-center items-center h-80 rounded-xl shadow-xl">
        <RoundButton />
      </div>
    </div>
  </div>
  </div>
</template>

<script lang="ts">
import Vue from 'vue'

export default Vue.extend({
})
</script>
