<template >


  <div id="about">
    <div class="p-5 mb-4 bg-body-tertiary" id="bgImg2345">
    
      <div class="container-fluid py-5">
        <h1 class="display-5 fw-bold text-black">About us</h1>

        <dividerComp />

        <p class="col-md-12 fs-4 mt-4 text-white container" data-aos="fade-up" data-aos-anchor-placement="center" id="mediaQtxt">
          With a combined experience of over two decades in investment management industry, our team collaborates closely with top-tier experts in legal, tax ,accounting, and financial planning.This collective expertise ensures comprehensive and informed guidance to navigate the complexities of your financial journey.
        </p>
        <p class="text-white" id="mediaQ"><q>Someone is sitting in the shade today because someone planted a tree long time ago</q> <br> <b>- Warren Buffet-</b> <br> @Twelve Two affirmation</p>
      </div>

   </div>


   <div class="container">

    <h1 class="display-5 fw-bold text-black">Our services</h1>

    <dividerComp />

   </div>
   
  <div id="abtSec" class="container" data-aos="fade-right" data-aos-anchor-placement="center">
    
    
    <div class="col-lg-4 pt-5">

      <div id="boxed" class="bd-placeholder-img rounded-circle">

        <i class="fa-solid fa-brain fa-2xl" style="color: #050505;" id="scaleIcon"></i>

      </div>

      <h2 class="fw-bold">Wealthy mind seminars</h2>

      <p>Practical strategies for effective financial management and integrational wealth building.</p>

    </div>

    <div class="col-lg-4 pt-5">
  
      <div id="boxed" class="bd-placeholder-img rounded-circle">

        <i class="fa-solid fa-chalkboard-user fa-2xl" style="color: #000000;" id="scaleIcon"></i>
                    
      </div>
                
      <h2 class="fw-bold">Individual Coaching</h2>
                
      <p>Personalized guidance on financial management, savings, investments, and achieving lasting financial freedom.Empowering individuals to focus on their life's purpose with financial confidence.</p>

    </div>
    
    <div class="col-lg-4 pt-5">

      <div id="boxed" class="bd-placeholder-img rounded-circle">

        <i class="fa-solid fa-coins fa-2xl" style="color: #000000;" id="scaleIcon"></i>
        
      </div>

      <h2 class="fw-bold">Rands and Sense</h2>

      <p>Monthly online series addressing diverse personal finance and business themes.</p>

    </div>
  </div>

  
  
  
  
  <div id="moreAbout" class="container">
    

    <div class="container my-4">
  
      <h1 class="display-5 fw-bold text-black">More about us</h1>
  
      <dividerComp />
  
    </div>

    
    <AboutSecTwo />
    
  </div>
  
  
  
  
  

  <div id="carousel" class="container mt-3 p-4 gap-4 d-flex justify-content-center">

      <div class="card mb-3" id="card">

        <div class="card-body">

          <div class="container my-2">

            <h1 class="display-5 fw-bold text-black">Insights</h1>
        
            <dividerComp />
        
          </div>

          <p class="card-text lead text-black-50">Insights that will be helpful when starting out with us!</p>

          <div class="d-flex justify-content-center" id="scroll">

            <div class="d-flex row mt-2 w-100">

              <div class="border border-2 rounded-3 p-1 mb-1" id="cardsm">

                <p class="text-white fw-bold fs-3">South Africans <br> broke and stressed</p>

                <a href="https://mg.co.za/news/2023-10-18-broke-and-stressed-south-africans-spiral-into-debt-trap/">

                  <GlobalBtnComp textContent="Go to link"/>

                </a>

              </div>

              <div class="border border-2 rounded-3 p-1 mb-1" id="cardsm">

                <p class="text-white fw-bold fs-3">Rachel Kolisi <br>on managing money</p>


                <a href="https://omny.fm/shows/other-peoples-money/other-people-s-money-rachel-kolisi-co-founder-of-k">

                  <GlobalBtnComp textContent="Go to link"/>

                </a>
              </div>

              <div class="border border-2 rounded-3 p-1 mb-1" id="cardsm">

                <p class="text-white fw-bold fs-3">Record keeping <br>for entrepreneurs</p>

                <a href="https://www.taxtim.com/za/blog/6-reasons-accounting-records-are-critical-to-your-small-business">

                  <GlobalBtnComp textContent="Go to link"/>

                </a>

              </div>

              <div class="border border-2 rounded-3 p-1 mb-1" id="cardsm">

                <p class="text-white fw-bold fs-3">Time- <br> the secret to long-term wealth creation</p>

                <a href="https://www.allangray.co.za/latest-insights/corporate-citizenship/time-the-greatest-gift-of-all/">

                  <GlobalBtnComp textContent="Go to link"/>

                </a>

              </div>

            </div>

          </div>

        </div>

      </div>
    
  </div>


  </div>
    
</template>
<script>
  import AOS from 'aos';
  import CarouselComp from './CarouselComp.vue';
  import dividerComp from './dividerComp.vue';
  import AboutSecTwo from './AboutSecTwo.vue';
  import GlobalBtnComp from './GlobalBtnComp.vue';
  import secondaryDivider from './secondaryDivider.vue';

export default {
  components: {
    CarouselComp,
    dividerComp,
    AboutSecTwo,
    GlobalBtnComp,
    secondaryDivider
  },
  mounted() {
    AOS.init();
  },
}
</script>
<style scoped>

  #about, #moreAbout{
    min-height: 100vh;
  }

  #bgImg2345{
    background-image: url('https://cdn-images.imagevenue.com/69/dc/36/ME17NVGW_o.png');
    background-repeat: no-repeat;
    background-size: cover;
    background-position: center;
    border-image: fill 1 linear-gradient(rgba(0, 0, 0, 0.616), #000000bd);
  }

  #card{
    background: rgba(255, 255, 255, 0.198);
    -webkit-backdrop-filter: blur(10px);
    backdrop-filter: blur(10px);
    border: 1px solid rgba(0, 0, 0, 0.146);
    box-shadow: 7px 7px 15px 1px rgba(0, 0, 0, 0.363);
  }

  #cardsm{
    background: linear-gradient(to left,rgb(0, 0, 0), rgb(34, 34, 34));
    border: 1px solid rgb(0, 0, 0) !important;
    margin-bottom: 18px !important;
  }


  #carousel{
    display: flex !important;
    max-width: 100% !important;
    background-image: url('https://cdn-images.imagevenue.com/21/a2/3e/ME17O37I_o.jpg');
    border-image: fill 0 linear-gradient(rgba(0, 0, 0, 0.243), rgba(0, 0, 0, 0.117));
    height: 450px;
    background-repeat: no-repeat;
    background-size: cover;
    background-position: center;
  }
  
  #txt{
    position: absolute;
    top: 7%;
    left: 0.3%;
    color: rgb(0, 0, 0);
  }
  
  #bottomSec{
    min-height: 100vh;
  }

  #abtSec{
    display: flex;
    justify-content: center;
  }
  .ul{
    height: 5px;
    width: 90px;
    background-color: rgb(133, 247, 107);
    position: absolute;
    box-shadow: 2px 2px 7px 2px rgba(0, 0, 0, 0.349);
    top: 12.6%;
    left: 0.3%;
  }
  [data-boxed]{
    min-height: 50vh;
    background-image: url("https://cdn-images.imagevenue.com/0c/da/8c/ME17KQ92_o.jpg");
    background-size: cover;
    background-repeat: no-repeat;
    filter: grayscale();
  }
  
  #scaleIcon{
    transform: scale(150%);
    margin-bottom: 30px;
    padding: 25px;
    border-radius: 50%;
  }
  
  #scaleIcon:hover{
    transform: scale(170%);
    transition: all 0.1s ease-in-out;
  }

  #btn{
    border: 1px solid rgba(0, 0, 0, 0);
    background: whitesmoke;
    color: rgb(0, 0, 0);
    font-weight: 600;
  }
  #btn:hover{
   /* background: linear-gradient(to right, #48DD22 30%, rgb(1, 1, 81)); */
    border: 1px solid rgb(9, 2, 82);
    color: rgb(9, 2, 82);
    font-weight: 600;
  }

  #scroll{
    overflow: scroll;
    height: 190px;
  }


  @media (max-width: 995px) {
    #abtSec{
      display: flex;
      justify-content: center;
      flex-direction: column;
    }
  }
  @media (max-width: 445px) {
    #abtSec{
      display: flex;
      justify-content: center;
      flex-direction: column;
    }

    #carousel{
      display: flex !important;
      max-width: 100% !important;
      background-image: url('https://cdn-images.imagevenue.com/21/a2/3e/ME17O37I_o.jpg');
      height: 550px;
      background-repeat: no-repeat;
      background-size: cover;
    }
    #scroll{
      overflow: scroll;
      height: 200px;
    }
    #card{
      color: white !important;
      width: 100%;
    }

    #mediaQ{
      font-size:0.7em;
    }

    #mediaQtxt{
      font-size: 1em !important;
      width: 100%;
      text-align: center;
      overflow: scroll;
      max-height: 145px;
    }
  }
  
</style>