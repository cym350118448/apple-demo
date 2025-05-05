<template>
  <section class="banner-iphone">
    <div class="iphone-title">iPhone</div>
    <div>
      <div class="iphone-desc">Meet the iPhone 16 family.</div>
    <a href="#" class="iphone-link button-primary">Learn more</a>
    <a href="#" class="iphone-link button-tertiary">Shop iPhone</a>
    </div>
    <div class="iphone-desc2 ai-gradient">Built for Apple Intelligence.</div>
    <!-- <img src="https://www.apple.com/v/home/bf/images/promos/iphone-15/promo_iphone15_announce__fmxxi8r9fkuy_large.jpg" alt="iPhone 16" class="iphone-img" /> -->
  </section>
</template>

<script setup>
</script>

<style scoped>
.banner-iphone {
  background: #f5f5f7;
  color: #000;
  text-align: center;
  padding: 40px 0 0 0;
  background-image: url('@/assets/hero_iphone_family__fuz5j2v5xx6y_large.jpg');
  background-position: center;
  background-repeat: no-repeat;
  height: 540px;
}
.iphone-title {
  font-size: 56px;
  font-weight: 600;
  margin-bottom: 8px;
  font-family: "SF Pro Display", "SF Pro Icons", "Helvetica Neue", "Helvetica", "Arial", sans-serif;
}
.iphone-desc {
  font-size: 32px;
  margin-bottom: 12px;
  font-family: "SF Pro Display", "SF Pro Icons", "Helvetica Neue", "Helvetica", "Arial", sans-serif;
}
.iphone-link {
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
.iphone-desc2 {
  font-size: 21px;
  line-height: 1.19048;
  /* font-weight: 400;
  letter-spacing: .011em; */
  font-family: "SF Pro Display", "SF Pro Icons", "Helvetica Neue", "Helvetica", "Arial", sans-serif;
  letter-spacing: 0;
  font-weight: 500 !important;
  margin-top: 27px;
}
.ai-gradient{
  /* background: -webkit-linear-gradient(356deg, #0090F7, #BA62FC, #F2416B, #F55600); */
  background: linear-gradient(94deg, #0090F7, #BA62FC, #F2416B, #F55600);
  /* -webkit-background-clip: text; */
  background-clip: text;
  color: transparent;
  display: inline-block;
}
.iphone-img {
  width: 400px;
  max-width: 90vw;
  margin: 32px auto 0 auto;
  display: block;
}
</style> 