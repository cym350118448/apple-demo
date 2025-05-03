<template>
  <section class="banner-watch">
    <div class="watch-title">
      <img src="@/assets/hero_logo_apple_watch_series_10__dla4dkv1wfue_large.png" alt="Apple Watch Series 10" class="watch-logo" />
      <div class="watch-desc">Thinstant classic.</div>
      <a href="#" class="watch-link button-primary">Learn more</a>
      <a href="#" class="watch-link button-tertiary">Buy</a>
    </div>
    <!-- <img src="@/assets/hero_apple_watch_series_10_avail_lte__esu66gaw6dci_large.jpg" alt="Apple Watch" class="watch-img" /> -->
  </section>
</template>

<script setup>
</script>

<style scoped>
.banner-watch {
  background: #f5f5f7;
  
  text-align: center;
  padding: 44px 0 0 0;
  height: 580px;
  background-image: url('@/assets/hero_apple_watch_series_10_avail_lte__esu66gaw6dci_large.jpg');
  background-position: center bottom;
  background-repeat: no-repeat;
}
.watch-title {
  margin-bottom: 16px;
  padding-top: 48px;
}
.watch-logo {
  height: 80%;
  margin-bottom: 0px;
}
.watch-desc {
    font-size: 28px;
    line-height: 1.14286;
    font-weight: 400;
    letter-spacing: .007em;
    font-family: "SF Pro Display", "SF Pro Icons", "Helvetica Neue", "Helvetica", "Arial", sans-serif;
    margin-top: 14px;
}
.watch-link {
    font-size: 17px;
    line-height: 1.17648;
    font-weight: 400;
    letter-spacing: -.022em;
    font-family: "SF Pro Text", "SF Pro Icons", "Helvetica Neue", "Helvetica", "Arial", sans-serif;
    border-style: solid;
    border-width: 1px;
    min-width: 28px;
    padding-left: 21px;
    padding-right: 21px;
    padding-top: 11px;
    padding-bottom: 11px;
    --sk-button-margin-horizontal: 18px;
    --sk-button-margin-vertical: 18px;
    cursor: pointer;
    display: inline-block;
    text-align: center;
    white-space: nowrap;
    white-space-collapse: collapse;
    text-wrap-mode: nowrap;
    text-decoration: none;
}
.button-primary{
    border-radius: 980px;
    background: #0071e3;
    color: #fff;
    border-color: rgba(0, 0, 0, 0);
    margin-top: 14px;
}
.button-tertiary{
    background: rgba(0, 0, 0, 0);
    color: #06c;
    border-color: #06c;
    border-radius: 980px;
    margin-left: 13px;
    margin-top: 14px;
}
.watch-img {
  width: 480px;
  max-width: 90vw;
  margin: 0 auto;
  display: block;
}
</style> 