<template>
  <div>
    <NavBar />
    <BannerWatch />
    <BannerIpad />
    <BannerIphone />
    <ProductGrid />
    <RecommendSection />
    <Footer />
  </div>
</template>

<script setup>
import NavBar from '@/components/NavBar.vue'
import BannerWatch from '@/components/BannerWatch.vue'
import BannerIpad from '@/components/BannerIpad.vue'
import BannerIphone from '@/components/BannerIphone.vue'
import ProductGrid from '@/components/ProductGrid.vue'
import RecommendSection from '@/components/RecommendSection.vue'
import Footer from '@/components/Footer.vue'
</script>

<style>
body {
  margin: 0;
  font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif;
  background: #f5f5f7;
}
</style>
