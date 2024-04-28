<template lang="">
    <div id="freeRes">
        <div class="container col-xxl-12 px-4 py-5">
            <div class="row flex-lg-row-reverse align-items-center g-5 py-5">
            <div class="col-10 col-sm-8 col-lg-6">
                <img src="https://cdn-images.imagevenue.com/fd/f2/b7/ME17OWEC_o.jpg" class="d-block mx-lg-auto img-fluid rounded-5 shadow adjust_img_width_to_screen" alt="@twelveTwo_Affirmation" width="700" height="500" loading="lazy">
            </div>
            <div class="col-lg-6 rounded-5 height_">
                <h1 class="display-5 fw-bold text-white lh-1 mb-3">Free resources <i class="fa-solid fa-book fa-sm fa-bounce" style="color: #fff;"></i></h1>
                <div class="container">
                    <CarouselComp />
                </div>
                <!-- <div class="d-grid gap-2 d-md-flex justify-content-md-start">
                <button type="button" class="btn btn-primary btn-lg px-4 me-md-2">Primary</button>
                <button type="button" class="btn btn-outline-secondary btn-lg px-4">Default</button>
                </div> -->
            </div>
            </div>
        </div>
    </div>
</template>
<script>
import CarouselComp from './CarouselComp.vue';
export default {
    components : {
        CarouselComp
    }
}
</script>
<style scoped>
    #freeRes{
        min-height: 100vh;
        display: flex;
        justify-content: center;
        align-items: center;
    }

    .justify{
        text-align: justify;
    }

    .height_{
        min-height: 550px;
        display: flex;
        justify-content: center;
        align-items: center;
        flex-direction: column;
        background: radial-gradient(rgb(120, 230, 104), hsla(233, 64%, 67%, 0.788));
    }

    @media (max-width: 376px) {
        .adjust_img_width_to_screen{
            min-width: 320px !important;
            height: 300px;
            object-fit: cover;
        }
    }

    @media (max-width: 326px) {
        .adjust_img_width_to_screen{
            min-width: 280px !important;
            height: 300px;
            object-fit: cover;
        }
    }
</style>