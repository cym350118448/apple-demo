<template>
  <div>
    <NavBar />
    <div class="homepage-section">
      <BannerWatch />
      <BannerIpad />
      <BannerIphone />
    </div>
    <AdList />
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
import AdList from '@/components/AdList.vue'
</script>
<style>
body {
  margin: 0;
  font-family: SF Pro Text,SF Pro Icons,Helvetica Neue,Helvetica,Arial,sans-serif;
  background: #f5f5f7;
}
@media screen and (max-width: 1.441e+06px) and (min-width: 1441px) {
        #app {
            --content-height: 580px;
            --columns: 2;
            --gutter-width: 12px;
            --gutter-half-width: 6px;
            --gutter-and-half-width: 18px;
            --gutter-color: #fff;
            --double-edge-border-width: 24px;
            --edge-border-width: 12px;
            --background-color: #f5f5f7;
            --text-color: #1d1d1f;
            --edge-border-width-fallback: 12px;
        }
    }
</style>
<style scoped>
.homepage-section{
  display: grid;
  grid-gap: 12px;
}
</style>
