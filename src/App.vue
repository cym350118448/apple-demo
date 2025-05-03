<template>
  <div>
    <NavBar />
    <div class="homepage-section">
      <BannerWatch />
      <BannerIpad />
      <BannerIphone />
    </div>
    <ProductGrid />
    <RecommendSection />
    <AppFooter />
  </div>
</template>

<script setup>
import NavBar from '@/components/NavBar.vue'
import BannerWatch from '@/components/BannerWatch.vue'
import BannerIpad from '@/components/BannerIpad.vue'
import BannerIphone from '@/components/BannerIphone.vue'
import ProductGrid from '@/components/ProductGrid.vue'
import RecommendSection from '@/components/RecommendSection.vue'
import AppFooter from '@/components/AppFooter.vue'
</script>
<style>
body {
  margin: 0;
  font-family: SF Pro Text,SF Pro Icons,Helvetica Neue,Helvetica,Arial,sans-serif;
  background: #f5f5f7;
}
</style>
<style scoped>
.homepage-section{
  display: grid;
  grid-gap: 12px;
}
</style>
