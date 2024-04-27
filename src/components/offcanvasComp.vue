<template>
<button id="button" class="btn" type="button" data-bs-toggle="offcanvas" data-bs-target="#offcanvasBottom" aria-controls="offcanvasBottom">Resources</button>

<div class="offcanvas offcanvas-bottom" tabindex="-1" id="offcanvasBottom" aria-labelledby="offcanvasBottomLabel">
  <div class="offcanvas-header">
    <h5 class="offcanvas-title" id="offcanvasBottomLabel">Our free resources</h5>
    <button type="button" class="btn-close" data-bs-dismiss="offcanvas" aria-label="Close"></button>
  </div>
  <div class="offcanvas-body container" id="cardsBody">

   <div id="cd" class="py-3 mb-3">
    <offcanvasCard cardContent="Get out of debt - Through our partnership with the dfree® Global Foundation, you get financial freedom lessons at your fingertips from virtually anywhere through the dfree® online Academy "/>
    <a class="btn bg-black text-white" target="_blank" href="https://academy.dfreefoundation.org/">Click here</a>
   </div>

  <div id="cd" class="py-3 mb-3">
    <offcanvasCard cardContent="Access your credit report - Experian provides free credit reports and free credit scores on My Credit Check"/>
      <a class="btn bg-black text-white" target="_blank" href="https://www.mycreditcheck.co.za/">Click here</a>
  </div>

  <div id="cd" class="py-3 mb-3">

    <offcanvasCard cardContent="Belong to a community savings club? Check out Stokfella for an easy tech savvy way of managing your group affairs."/>
      
      <a class="btn bg-black text-white" target="_blank" href="https://www.stokfella.com/">Click here</a>

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
<style scoped>
    #offcanvasBottom{
      background-color: rgba(255, 255, 255, 0.291);
      -webkit-backdrop-filter: blur(20px);
      backdrop-filter: blur(20px);
      color: white;
      z-index: 9999 !important;
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
      border: 1px solid black;
    }

    #cardsBody{
      display: flex;
      justify-content: center;
      flex-wrap: wrap;
    }

    @media (max-width: 550px) {
      #cardsBody{
        display: flex;
        justify-content: center;

      }
    }
</style>