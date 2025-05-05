<template>
  <section class="banner-ipad">
    <div class="ipad-title">iPad Pro</div>
    <div class="ipad-desc">Unbelievably thin. Incredibly powerful.</div>
    <div>
      <a href="#" class="ipad-link button-primary">Learn more</a>
      <a href="#" class="ipad-link button-tertiary">Buy</a>
    </div>
    <div class="ipad-desc2 ai-gradient">Built for Apple Intelligence.</div>
    <!-- <img src="https://www.apple.com/v/home/bf/images/promos/ipad-pro/promo_ipadpro__ch217v9v7no2_large.jpg" alt="iPad Pro" class="ipad-img" /> -->
  </section>
</template>

<script setup>
</script>

<style scoped>
.banner-ipad {
  background: #000;
  color: #fff;
  text-align: center;
  padding: 40px 0 0 0;
  background-image: url('@/assets/hero_ipadpro_avail__d6ddfjws77ue_large.jpg');
  background-position: center;
  background-repeat: no-repeat;
  /* /* width: 3008px; */
  height: 540px;
}
.ipad-title {
  font-size: 40px;
  font-weight: 600;
  margin-bottom: 8px;
}
.ipad-desc {
  font-size: 20px;
  margin-bottom: 12px;
}
.ipad-link {
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
.ipad-desc2 {
  font-size: 21px;
  line-height: 1.19048;
  /* font-weight: 400;
  letter-spacing: .011em; */
  font-family: "SF Pro Display", "SF Pro Icons", "Helvetica Neue", "Helvetica", "Arial", sans-serif;
  letter-spacing: 0;
  font-weight: 500 !important;
  margin-top: 330px;
}
.ai-gradient{
  /* background: -webkit-linear-gradient(356deg, #0090F7, #BA62FC, #F2416B, #F55600); */
  background: linear-gradient(94deg, #0090F7, #BA62FC, #F2416B, #F55600);
  /* -webkit-background-clip: text; */
  background-clip: text;
  color: transparent;
  display: inline-block;
}
.ipad-img {
  width: 600px;
  max-width: 95vw;
  margin: 32px auto 0 auto;
  display: block;
}
</style> 