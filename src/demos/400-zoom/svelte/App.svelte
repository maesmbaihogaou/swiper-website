<script>
  import { Swiper, SwiperSlide } from "swiper/svelte";

  // Import Swiper styles
  import "swiper/css";

  import "swiper/css/zoom";
  import "swiper/css/navigation";
  import "swiper/css/pagination";

  import "./style.css";

  // import required modules
  import { Zoom, Navigation, Pagination } from "swiper";
</script>

<Swiper
  style="--swiper-navigation-color: #fff;--swiper-pagination-color: #fff"
  zoom={true}
  navigation={true}
  pagination={{
    clickable: true,
  }}
  modules={[Zoom, Navigation, Pagination]}
  class="mySwiper"
>
  <SwiperSlide>
    <div class="swiper-zoom-container">
      <img src="https://swiperjs.com/demos/images/nature-1.jpg" />
    </div>
  </SwiperSlide><SwiperSlide>
    <div class="swiper-zoom-container">
      <img src="https://swiperjs.com/demos/images/nature-2.jpg" />
    </div>
  </SwiperSlide><SwiperSlide>
    <div class="swiper-zoom-container">
      <img src="https://swiperjs.com/demos/images/nature-3.jpg" />
    </div>
  </SwiperSlide><SwiperSlide>
    <div class="swiper-zoom-container">
      <img src="https://swiperjs.com/demos/images/nature-4.jpg" />
    </div>
  </SwiperSlide><SwiperSlide>
    <div class="swiper-zoom-container">
      <img src="https://swiperjs.com/demos/images/nature-5.jpg" />
    </div>
  </SwiperSlide><SwiperSlide>
    <div class="swiper-zoom-container">
      <img src="https://swiperjs.com/demos/images/nature-6.jpg" />
    </div>
  </SwiperSlide><SwiperSlide>
    <div class="swiper-zoom-container">
      <img src="https://swiperjs.com/demos/images/nature-7.jpg" />
    </div>
  </SwiperSlide><SwiperSlide>
    <div class="swiper-zoom-container">
      <img src="https://swiperjs.com/demos/images/nature-8.jpg" />
    </div>
  </SwiperSlide><SwiperSlide>
    <div class="swiper-zoom-container">
      <img src="https://swiperjs.com/demos/images/nature-9.jpg" />
    </div>
  </SwiperSlide>
</Swiper>
