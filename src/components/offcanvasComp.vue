<template>
<button id="button" class="btn" type="button" data-bs-toggle="offcanvas" data-bs-target="#offcanvasBottom" aria-controls="offcanvasBottom">Resources</button>

<div class="offcanvas offcanvas-bottom" tabindex="-1" id="offcanvasBottom" aria-labelledby="offcanvasBottomLabel">
  <div class="offcanvas-header">
    <h5 class="offcanvas-title" id="offcanvasBottomLabel">Our free resources</h5>
    <button type="button" class="btn-close" data-bs-dismiss="offcanvas" aria-label="Close"></button>
  </div>
  <div class="offcanvas-body small d-flex justify-content-evenly">
   <div id="cd">
    <offcanvasCard cardContent="Hlloe"/>
    <!-- https://academy.dfreefoundation.org/ -->
   </div>
  <div id="cd">
    <offcanvasCard cardContent="Hlloe"/>
      <!-- https://www.mycreditcheck.co.za/ -->
  </div>
  <div id="cd">
    <offcanvasCard cardContent="Hlloe"/>
      <!-- https://www.stokfella.com/ -->
  </div>
  </div>
</div>
</template>
<script>
import offcanvasCard from './offcanvasCard.vue';

export default {
    components : {
      offcanvasCard
    }
}
</script>
<style>
    #offcanvasBottom{
      background-color: rgba(255, 255, 255, 0.291);
      -webkit-backdrop-filter: blur(20px);
      backdrop-filter: blur(20px);
      color: white;
    }

    #button{
      background: radial-gradient(circle, rgb(50, 212, 53), rgb(50, 212, 13));
      color: white;
    }
    #button:hover{
      transform: scale(110%);
      transition: all 0.1s ease-in-out;
    }
    #cd{
      width: 100%;
    }
</style>