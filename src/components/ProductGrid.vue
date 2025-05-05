<template>
  <section class="product-grid">
    <div class="grid-container">
      <div class="grid-item grid-mother">
        <div class="botton-unit">
          <div class="title">Mother's Day</div>
          <div class="desc">Find the perfect gift for Mom.</div>
          <a href="#" class="link button-primary button-group">Shop</a>
        </div>
      </div>
      <div class="grid-item grid-macbook">
        <div class="title">MacBook Air</div>
        <div class="desc">Sky blue color.<br>Sky high performance with M4.</div>
        <div class="button-group">
          <a href="#" class="link button-primary">Learn more</a>
          <a href="#" class="link button-tertiary">Buy</a>
        </div>
        <div class="desc2 ai-gradient">Built for Apple Intelligence.</div>
      </div>
      <div class="grid-item grid-ipad">
        <!-- <div class="title">Mac does that.</div> -->
        <img src="@/assets/promo_logo_ipadair__frwnnsqveeye_large.png" alt="iPad Air" class="ipad-logo">
        <div class="desc">Now supercharged by the M3 chip.</div>
        <div class="button-group">
          <a href="#" class="link button-primary">Learn more</a>
          <a href="#" class="link button-tertiary">Buy</a>
        </div>
        <div class="desc2 ai-gradient">Built for Apple Intelligence.</div>
      </div>
      <div class="grid-item grid-tradein">
        <div class="title">Apple Trade In</div>
        <div class="desc">Get $170–$630 in credit when you trade in iPhone 12 or higher.</div>
        <a href="#" class="link button-primary button-group">Get your estimate</a>
      </div>
      <div class="grid-item grid-carrier">
        <div class="botton-unit">
          <div class="title">Carrier deals at Apple</div>
          <div class="desc">Get up to $1000 in credit on a new iPhone. Trade-in may be required.</div>
          <a href="#" class="link button-primary button-group">Find your deal</a>
        </div>
      </div>
      <div class="grid-item grid-card">
        <div class="title">Apple Card</div>
        <div class="desc">Get up to 3% Daily Cash back with every purchase.</div>
        <div class="button-group">
          <a href="#" class="link button-primary button-group">Learn more</a>
          <a href="#" class="link button-primary button-tertiary">Apply now</a>
        </div>
      </div>
    </div>
  </section>
</template>

<script setup>
</script>

<style scoped>
.product-grid {
  background: #fff;
  padding: 12px 0;
  display: flex;
  justify-content: center;
}
.grid-container {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  grid-template-rows: repeat(3, 1fr);
  gap: 12px;
  width: 100%;
}
.grid-item {
  background: #f5f5f7;
  /* border-radius: 0px; */
  box-shadow: 0 2px 8px rgba(0,0,0,0.04);
  /* padding: 24px; */
  text-align: center;
  display: flex;
  flex-direction: column;
  align-items: center;
  min-height: 180px;
  height: var(--content-height);
}
.grid-mother {
  background-image: url('@/assets/hero_md25__ca4cocy2qlv6_large.png');
  background-position: center;
  background-repeat: no-repeat;
}
.grid-macbook{
  background-image: url('@/assets/promo_macbook_air_avail__e8ksaudoisey_large.jpg');
  width: 1262px;
  height: 580px;
  background-size: 1262px 580px;
  background-repeat: no-repeat;
}
.grid-ipad{
  background-image: url('@/assets/promo_ipad_air__bfbxzvw65c02_large.jpg');
  width: 1262px;
  height: 580px;
  background-size: 1262px 580px;
  background-repeat: no-repeat;
}
.grid-tradein{
  background-image: url('@/assets/promo_iphone_tradein__bugw15ka691e_large.jpg');
  width: 1262px;
  height: 580px;
  background-size: 1262px 580px;
  background-repeat: no-repeat; 
}
.grid-carrier{
  background-image: url('@/assets/promo_carrier__e0izvxwqosgi_large.jpg');
  width: 1262px;
  height: 580px;
  background-size: 1262px 580px;
  background-repeat: no-repeat; 
}
.grid-card{
  background-image: url('@/assets/promo_apple_card_gradient__f2e2582vf1u2_large.jpg');
  width: 1262px;
  height: 580px;
  background-size: 1262px 580px;
  background-repeat: no-repeat; 
}
.grid-item img {
  width: 120px;
  margin-bottom: 12px;
}
.title {
  /* font-size: 20px;
  font-weight: 600;
  margin-bottom: 8px; */
  font-size: 40px;
  line-height: 1.1;
  font-weight: 600;
  letter-spacing: 0em;
  font-family: "SF Pro Display", "SF Pro Icons", "Helvetica Neue", "Helvetica", "Arial", sans-serif;
  margin-top: 53px;
}
.desc {
  /* font-size: 14px;
  color: #555;
  margin-bottom: 12px; */
  font-size: 21px;
  line-height: 1.19048;
  font-weight: 400;
  letter-spacing: .011em;
  font-family: "SF Pro Display", "SF Pro Icons", "Helvetica Neue", "Helvetica", "Arial", sans-serif;
  margin-top: 4px;
}
.desc2 {
  font-size: 14px;
  line-height: 1.28577;
  font-weight: 400;
  letter-spacing: -.016em;
  font-family: "SF Pro Text", "SF Pro Icons", "Helvetica Neue", "Helvetica", "Arial", sans-serif;
  letter-spacing: 0;
  font-weight: 500 !important;
  margin-top: 320px;
}
.ai-gradient{
  /* background: -webkit-linear-gradient(356deg, #0090F7, #BA62FC, #F2416B, #F55600); */
  background: linear-gradient(94deg, #0090F7, #BA62FC, #F2416B, #F55600);
  /* -webkit-background-clip: text; */
  background-clip: text;
  color: transparent;
  display: inline-block;
}
.link {
  cursor: pointer;
  display: inline-block;
  text-align: center;
  white-space: nowrap;
  font-size: 17px;
  line-height: 1.17648;
  font-weight: 400;
  letter-spacing: -.022em;
  font-family: "SF Pro Text", "SF Pro Icons", "Helvetica Neue", "Helvetica", "Arial", sans-serif;
  border-style: solid;
  border-width: 1px;
  min-width: 30px;
  padding-left: 15px;
  padding-right: 15px;
  padding-top: 7px;
  padding-bottom: 7px;
  border-radius: 980px;
  background: #0071e3;
  color: #fff;
  border-color: rgba(0, 0, 0, 0);
  --sk-button-margin-horizontal: 14px;
  --sk-button-margin-vertical: 14px;
  text-decoration: none;
  white-space-collapse: collapse;
  text-wrap-mode: nowrap;
}
.button-group {
  display: flex;
  justify-content: center;
  gap: 13px;
  margin-top: 17px;
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
@media (max-width: 900px) {
  .grid-container {
    grid-template-columns: 1fr;
    width: 98vw;
  }
}
.ipad-logo {
  width: 200px;
  margin-top: 58px;
  margin-bottom: 10px;
}
.botton-unit{
  margin-top: 300px;
}
</style> 