<template>

  <swiper
    :slidesPerView="1"
    :spaceBetween="30"
    :loop="true"
    :pagination="{
      clickable: true,
    }"
    :navigation="true"
    :modules="modules"
    class="mySwiper my-3 shadow rounded-2"
  >
    <swiper-slide class="height_slide rounded-2 apply_primary_company_color">Slide 1</swiper-slide>

    <swiper-slide class="height_slide rounded-2 apply_primary_company_color">Slide 2</swiper-slide>

    <swiper-slide class="height_slide rounded-2 apply_primary_company_color">Slide 3</swiper-slide>

    <swiper-slide class="height_slide rounded-2 apply_primary_company_color">Slide 4</swiper-slide>

    <swiper-slide class="height_slide rounded-2 apply_primary_company_color">Slide 5</swiper-slide>

    <swiper-slide class="height_slide rounded-2 apply_primary_company_color">Slide 6</swiper-slide>

    <swiper-slide class="height_slide rounded-2 apply_primary_company_color">Slide 7</swiper-slide>

    <swiper-slide class="height_slide rounded-2 apply_primary_company_color">Slide 8</swiper-slide>

    <swiper-slide class="height_slide rounded-2 apply_primary_company_color">Slide 9</swiper-slide>

  </swiper>

</template>
<script>
  // Import Swiper Vue.js components
  import { Swiper, SwiperSlide } from 'swiper/vue';

  // Import Swiper styles
  import 'swiper/css';

  import 'swiper/css/pagination';
  import 'swiper/css/navigation';

  // import required modules
  import { Pagination, Navigation } from 'swiper/modules';

  export default {
    components: {
      Swiper,
      SwiperSlide,
    },
    setup() {
      return {
        modules: [Pagination, Navigation],
      };
    },
  };
</script>
<style scoped>

  .height_slide{
    height: 300px;
    width: 100%;
    display: flex;
    justify-content: center;
    align-items: center;
  }

  .apply_primary_company_color{
    background-color: rgb(120, 167, 255);
  }

</style>