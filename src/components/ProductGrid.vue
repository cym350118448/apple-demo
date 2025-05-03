<template>
  <section class="product-grid">
    <div class="grid-container">
      <div class="grid-item grid-mother">
        <div class="title">Mother's Day</div>
        <div class="desc">Find the perfect gift for Mom.</div>
        <a href="#" class="link">Shop</a>
      </div>
      <div class="grid-item grid-macbook">
        <div class="title">MacBook Air</div>
        <div class="desc">Sky blue color.<br>Sky high performance with M4.</div>
        <a href="#" class="link">Learn more</a>
        <a href="#" class="link">Buy</a>
        <div class="desc2">Built for Apple Intelligence.</div>
      </div>
      <div class="grid-item grid-mac">
        <div class="title">Mac does that.</div>
        <div class="desc">See how easy it is to switch to Mac.</div>
        <a href="#" class="link">Learn more</a>
      </div>
      <div class="grid-item grid-tradein">
        <div class="title">Apple Trade In</div>
        <div class="desc">Get $170–$630 in credit when you trade in iPhone 12 or higher.</div>
        <a href="#" class="link">Get your estimate</a>
      </div>
      <div class="grid-item grid-carrier">
        <div class="title">Carrier deals at Apple</div>
        <div class="desc">Get up to $1000 in credit on a new iPhone. Trade-in may be required.</div>
        <a href="#" class="link">Find your deal</a>
      </div>
      <div class="grid-item grid-card">
        <div class="title">Apple Card</div>
        <div class="desc">Get up to 3% Daily Cash back with every purchase.</div>
        <a href="#" class="link">Learn more</a>
        <a href="#" class="link">Apply now</a>
      </div>
    </div>
  </section>
</template>

<script setup>
</script>

<style scoped>
.product-grid {
  background: #fff;
  padding: 32px 0;
  display: flex;
  justify-content: center;
}
.grid-container {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  grid-template-rows: repeat(3, 1fr);
  gap: 24px;
  width: 900px;
  max-width: 98vw;
}
.grid-item {
  background: #f5f5f7;
  border-radius: 16px;
  box-shadow: 0 2px 8px rgba(0,0,0,0.04);
  padding: 24px;
  text-align: center;
  display: flex;
  flex-direction: column;
  align-items: center;
  min-height: 180px;
}
.grid-item img {
  width: 120px;
  margin-bottom: 12px;
}
.title {
  font-size: 20px;
  font-weight: 600;
  margin-bottom: 8px;
}
.desc {
  font-size: 14px;
  color: #555;
  margin-bottom: 12px;
}
.desc2 {
  font-size: 12px;
  color: #888;
  margin-bottom: 8px;
}
.link {
  color: #2997ff;
  text-decoration: none;
  font-size: 15px;
  margin: 0 8px;
}
@media (max-width: 900px) {
  .grid-container {
    grid-template-columns: 1fr;
    width: 98vw;
  }
}
</style> 