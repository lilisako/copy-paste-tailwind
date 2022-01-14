<template class="h-screen">
  <div class="py-16 px-4 md:px-14">
    <!-- start header -->
    <div class="flex justify-between pl-4">
      <NuxtLink to="/">
        <div class="flex items-center">
          <span class="mx-1 text-4xl material-icons">content_copy</span>
          <h1 class="font-bold md:text-2xl">
            Copy-Paste Tailwind
          </h1>
        </div>
      </NuxtLink>
    </div>
    <!-- end header -->
    <div class="grid grid-cols-1 md:grid-cols-2">
      <Showcase hashtag="crypto-price-card" url="https://github.com/lilisako/copy-paste-tailwind">
        <CryptoCard />
      </Showcase>
      <Showcase hashtag="news-article-card" url="https://github.com/lilisako/copy-paste-tailwind">
        <NewsArticleCard />
      </Showcase>
      <Showcase hashtag="appointment-button" url="https://github.com/lilisako/copy-paste-tailwind">
        <AppointmentButton />
      </Showcase>
      <Showcase hashtag="social-profile" url="https://github.com/lilisako/copy-paste-tailwind/blob/main/components/profile.vue#L2-L14">
        <Profile />
      </Showcase>
    </div>
  </div>
</template>

<script>

import Vue from 'vue'
export default Vue.extend({
})
</script>
