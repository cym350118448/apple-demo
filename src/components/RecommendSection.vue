<template>
  <section class="recommend-section">
    <div class="recommend-scroll">
      <div class="recommend-item">
        <img src="https://www.apple.com/v/home/bf/images/tv-plus-gallery/friends-neighbors/promo_friends_neighbors__f5gk6x7b1y6y_large.jpg" alt="Your Friends & Neighbors" />
        <div class="recommend-title">YOUR FRIENDS & NEIGHBORS</div>
      </div>
      <div class="recommend-item">
        <img src="https://www.apple.com/v/home/bf/images/tv-plus-gallery/the-studio/promo_the_studio__e7x1v1v1v1v1_large.jpg" alt="The Studio" />
        <div class="recommend-title">The Studio</div>
      </div>
      <!-- 可继续添加更多推荐项 -->
    </div>
  </section>
</template>

<script setup>
</script>

<style scoped>
.recommend-section {
  background: #fff;
  padding: 32px 0;
  overflow-x: auto;
}
.recommend-scroll {
  display: flex;
  gap: 24px;
  overflow-x: auto;
  padding: 0 24px;
}
.recommend-item {
  min-width: 320px;
  background: #222;
  border-radius: 12px;
  color: #fff;
  text-align: center;
  box-shadow: 0 2px 8px rgba(0,0,0,0.08);
  padding-bottom: 16px;
}
.recommend-item img {
  width: 100%;
  border-radius: 12px 12px 0 0;
}
.recommend-title {
  font-size: 18px;
  font-weight: 600;
  margin: 12px 0 0 0;
}
</style> 