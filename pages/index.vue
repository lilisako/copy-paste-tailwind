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
      <Showcase hashtag="customer-review-card" url="customer-review.vue#L2-L9">
        <CustomerReview />
      </Showcase>
      <Showcase hashtag="crypto-price-card" url="crypto-card.vue#L2-L14">
        <CryptoCard />
      </Showcase>
      <Showcase hashtag="news-article-card" url="news-article-card.vue#L2-L39">
        <NewsArticleCard />
      </Showcase>
      <Showcase hashtag="appointment-button" url="appointment-button.vue#L2-L38">
        <AppointmentButton />
      </Showcase>
      <Showcase hashtag="social-profile" url="profile.vue#L2-L14">
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
