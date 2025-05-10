<template>
  <swiper
    slidesPerView="auto"
    :spaceBetween="30"
    :pagination="{
      clickable: true,
    }"
    :modules="modules"
    class="myswiper"
    :centeredSlides="true"
    :setWrapperSize="true"
  >
    <swiper-slide>
        <div>
            <img src="@/assets/adlist/2500x1406.jpg" alt="">
        </div>
    </swiper-slide>
    <swiper-slide>
        <img src="@/assets/adlist/2500x1406.jpg" alt="">
    </swiper-slide>
    <swiper-slide>
        <img src="@/assets/adlist/2500x1406.jpg" alt="">
    </swiper-slide>
    <swiper-slide>
        <img src="@/assets/adlist/2500x1406.jpg" alt="">
    </swiper-slide>
    <swiper-slide>
        <img src="@/assets/adlist/2500x1406.jpg" alt="">
    </swiper-slide>
  </swiper>
</template>
<script>
// Import Swiper Vue.js components
import { Swiper, SwiperSlide } from "swiper/vue";

// Import Swiper styles
import "swiper/css";

import "swiper/css/pagination";

// import required modules
import { Pagination } from "swiper/modules";

export default {
  components: {
    Swiper,
    SwiperSlide,
  },
  setup() {
    return {
      modules: [Pagination],
    };
  },
};
</script>
<style>
.swiper {
  width: 100%;
  /* height: 667px; */
  padding-bottom: 50px;
  background-color: #fff;
}

.swiper-slide {
  width: 1256px !important;
  text-align: center;
  font-size: 18px;
  background: #fff;

  display: flex;
  justify-content: center;
  align-items: center;
  opacity: 0.3;
}

.swiper-slide-active{
    opacity: 1;
}

.swiper-slide img {
  display: block;
  width: 100%;
  height: 100%;
  object-fit: cover;
}
</style>


<!-- <template>
    <swiper :modules="modules" :slides-per-view="3" :space-between="50" navigation :pagination="{ clickable: true }"
        :scrollbar="{ draggable: true }" @swiper="onSwiper" @slideChange="onSlideChange" :centeredSlides="true"
        :centeredSlidesBounds="true" slideActiveClass="adlist-swiper-slide-active">
        <swiper-slide class="adlist-swiper-slide">
            <img class="slide-img" src="@/assets/adlist/2500x1406.jpg" />
        </swiper-slide>
        <swiper-slide class="adlist-swiper-slide"><img class="slide-img"
                src="@/assets/adlist/2500x1406.jpg" /></swiper-slide>
        <swiper-slide class="adlist-swiper-slide"><img class="slide-img"
                src="@/assets/adlist/2500x1406.jpg" /></swiper-slide>
        <swiper-slide class="adlist-swiper-slide"><img class="slide-img"
                src="@/assets/adlist/2500x1406.jpg" /></swiper-slide>
        <swiper-slide class="adlist-swiper-slide"><img class="slide-img"
                src="@/assets/adlist/2500x1406.jpg" /></swiper-slide>
    </swiper>
</template>
<script>
// import Swiper core and required modules
import { Navigation, Pagination, Scrollbar, A11y } from 'swiper/modules';

// Import Swiper Vue.js components
import { Swiper, SwiperSlide } from 'swiper/vue';

// Import Swiper styles
import 'swiper/css';
import 'swiper/css/navigation';
import 'swiper/css/pagination';
import 'swiper/css/scrollbar';

// Import Swiper styles
export default {
    components: {
        Swiper,
        SwiperSlide,
    },
    setup() {
        const onSwiper = (swiper) => {
            console.log(swiper);
        };
        const onSlideChange = () => {
            console.log('slide change');
        };
        return {
            onSwiper,
            onSlideChange,
            modules: [Navigation, Pagination, Scrollbar, A11y],
        };
    },
};
</script>
<style scoped>
.adlist-swiper-slide {
    /* width: 1250px !important;
    height: 667px; */
}

.slide-img {
    width: 1250px;
    height: 667px;
}

.adlist-swiper-slide-active {
    /* width: 1250px !important;
    height: 667px; */
}
</style> -->