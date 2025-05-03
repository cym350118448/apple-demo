<template>
  <nav class="navbar">
    <ul class="navbar-list">
      <li class="icon">
        <!-- Apple Logo SVG -->
        <svg height="44" viewBox="0 0 14 44" fill="currentColor">
          <path
            d="m13.0729 17.6825a3.61 3.61 0 0 0-1.7248 3.0365 3.5132 3.5132 0 0 0 2.1379 3.2223 8.394 8.394 0 0 1-1.0948 2.2618c-.6816.9812-1.3943 1.9623-2.4787 1.9623s-1.3633-.63-2.613-.63c-1.2187 0-1.6525.6507-2.644.6507s-1.6834-.9089-2.4787-2.0243a9.7842 9.7842 0 0 1-1.6628-5.2776c0-3.0984 2.014-4.7405 3.9969-4.7405 1.0535 0 1.9314.6919 2.5924.6919.63 0 1.6112-.7333 2.8092-.7333a3.7579 3.7579 0 0 1 3.1604 1.5802zm-3.7284-2.8918a3.5615 3.5615 0 0 0 .8469-2.22 1.5353 1.5353 0 0 0-.031-.32 3.5686 3.5686 0 0 0-2.3445 1.2084 3.4629 3.4629 0 0 0-.8779 2.1585 1.419 1.419 0 0 0 .031.2892 1.19 1.19 0 0 0 .2169.0207 3.0935 3.0935 0 0 0 2.1586-1.1368z" />
        </svg>
      </li>
      <li>Store</li>
      <li>Mac</li>
      <li>iPad</li>
      <li>iPhone</li>
      <li>Watch</li>
      <li>Vision</li>
      <li>AirPods</li>
      <li>TV & Home</li>
      <li>Entertainment</li>
      <li>Accessories</li>
      <li>Support</li>
      <li class="icon right">
        <!-- Search SVG -->
        <svg height="44" viewBox="0 0 15 44">
          <path
            d="M14.298,27.202l-3.87-3.87c0.701-0.929,1.122-2.081,1.122-3.332c0-3.06-2.489-5.55-5.55-5.55c-3.06,0-5.55,2.49-5.55,5.55 c0,3.061,2.49,5.55,5.55,5.55c1.251,0,2.403-0.421,3.332-1.122l3.87,3.87c0.151,0.151,0.35,0.228,0.548,0.228 s0.396-0.076,0.548-0.228C14.601,27.995,14.601,27.505,14.298,27.202z M1.55,20c0-2.454,1.997-4.45,4.45-4.45 c2.454,0,4.45,1.997,4.45,4.45S8.454,24.45,6,24.45C3.546,24.45,1.55,22.454,1.55,20z"
            fill="currentColor" />
        </svg>
      </li>
      <li class="icon right">
        <!-- Bag SVG -->
        <!-- <svg width="14" height="44" viewBox="0 0 14 44" fill="none"><path d="m11.3535 16.0283h-1.0205a3.4229 3.4229 0 0 0 -3.333-2.9648 3.4229 3.4229 0 0 0 -3.333 2.9648h-1.02a2.1184 2.1184 0 0 0 -2.117 2.1162v7.7155a2.1186 2.1186 0 0 0 2.1162 2.1167h8.707a2.1186 2.1186 0 0 0 2.1168-2.1167v-7.7155a2.1184 2.1184 0 0 0 -2.1165-2.1162zm-4.3535-1.8652a2.3169 2.3169 0 0 1 2.2222 1.8652h-4.4444a2.3169 2.3169 0 0 1 2.2222-1.8652zm5.37 11.6969a1.0182 1.0182 0 0 1 -1.0166 1.0171h-8.7069a1.0182 1.0182 0 0 1 -1.0165-1.0171v-7.7155a1.0178 1.0178 0 0 1 1.0166-1.0166h8.707a1.0178 1.0178 0 0 1 1.0164 1.0166z" stroke="currentColor" stroke-width="1.3" stroke-linecap="round" stroke-linejoin="round"/></svg> -->
        <a role="button" id="globalnav-menubutton-link-bag" href="/us/shop/goto/bag" aria-label="Shopping Bag"
          data-globalnav-item-name="bag" data-topnav-flyout-trigger-regular="true"
          data-topnav-flyout-trigger-compact="true" data-analytics-title="open - bag"
          class="globalnav-link globalnav-link-bag">
          <span class="globalnav-image-regular">
            <svg height="44"
              viewBox="0 0 14 44" width="14" xmlns="http://www.w3.org/2000/svg">
              <path
                d="m11.3535 16.0283h-1.0205a3.4229 3.4229 0 0 0 -3.333-2.9648 3.4229 3.4229 0 0 0 -3.333 2.9648h-1.02a2.1184 2.1184 0 0 0 -2.117 2.1162v7.7155a2.1186 2.1186 0 0 0 2.1162 2.1167h8.707a2.1186 2.1186 0 0 0 2.1168-2.1167v-7.7155a2.1184 2.1184 0 0 0 -2.1165-2.1162zm-4.3535-1.8652a2.3169 2.3169 0 0 1 2.2222 1.8652h-4.4444a2.3169 2.3169 0 0 1 2.2222-1.8652zm5.37 11.6969a1.0182 1.0182 0 0 1 -1.0166 1.0171h-8.7069a1.0182 1.0182 0 0 1 -1.0165-1.0171v-7.7155a1.0178 1.0178 0 0 1 1.0166-1.0166h8.707a1.0178 1.0178 0 0 1 1.0164 1.0166z">
              </path>
            </svg>
          </span>
        </a>
      </li>
    </ul>
  </nav>
</template>

<script setup>
</script>

<style scoped>
.navbar {
  cursor: default;
  margin: 0 -8px;
  width: 100%;
  height: 44px;
  display: flex;
  justify-content: center;
  user-select: none;
  list-style: none;
  position: fixed;
  top: 0;
  background-color: rgba(250, 250, 252, .8);
}

.navbar-list {
  display: flex;
  gap: 24px;
  list-style: none;
  padding: 0;
  margin: 0 auto;
  box-sizing: border-box;
  max-width: 1024px;
  color: #000;
  align-items: center;
  width: 100%;
  padding: 0 22px;
  justify-content: space-between;
}

.navbar-list li {
  cursor: pointer;
  opacity: 0.8;
  transition: opacity 0.3s;
  color: #000;
  font-size: 12px;
}

.navbar-list li:hover {
  opacity: 1;
}

.icon {
  display: flex;
  align-items: center;
}

.icon svg {
  width: 16px;
  height: 44px;
  color: #000;
}

.icon.right {
  /* margin-left: auto; */
}

.icon.right+.icon.right {
  /* margin-left: 24px; */
}
</style>