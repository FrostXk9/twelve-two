<template>

  <div class="position-relative overflow-hidden text-center" id="landingPage" loading="lazy">

    <div class="col-md-12 p-lg-2 mx-auto container" id="childpg34">
      
      
      
      <div class="display-1 fw-bold text-black my-1" id="fontify">
        Twelve Two <span id="floatLikeInt">2</span>
      </div>
      
      <div id="rotate">
        <div class="rtpov">
          <p class="fw-bold text-white">Financial</p>
          <div id="words">
            <span class="word">Knowledge</span>
            <span class="word">Coaching</span>
            <span class="word">Freedom</span>
            <span class="word">Mindset</span>
            <span class="word">Resillience</span>
          </div>
        </div>
      </div>
      
        <div class="display-5 fw-bold text-white">
          Get expert advice on how to manage your money 
        </div>
  
        <!-- <p class="fw-bold text-black text-center mb-2 px-5 mx-3">Twelve two is dedicated to empowering individuals on their financial journey through coaching.Our mission is to demystify personal finance, fostering confidence and success. <br> Guided by a commitment to holistic financial wellness, we provide tailored coaching services, equipping clients with practical tools and strategies for spending plans,investing,and debt elimination. <br> At Twelve Two, we belive in a collaborative approach, working alongside you to transform financial goals into achievable realities.Let us be your partner in navigating the path to financial well-being</p> -->
        
        <!-- <details>
          <summary>Text</summary>
          something about this bussiness
        </details> -->
        
        <div class="mb-4">

          <h3 class="text-white">Stay updated with us <i class="fa-regular fa-calendar-check fa-lg" style="color: rgb(53, 230, 3);"></i></h3>

          <p class="small text-center text-white-50">Build your knowledge today!</p>

        </div>

        <div class="d-flex gap-5 mb-4 justify-content-center lead fw-normal mt-1">
  
          <ButtonComp />
  
        </div>


        
        <div id="icw221">
          <div class="fw-normal text-white">
            Get to know us more
          </div>
          <a href="#moreAbout">
            <img src="https://cdn-images.imagevenue.com/1c/cd/f0/ME17OW6E_o.png" alt="Double Down.png">
          </a>
        </div>


        
      </div>

      <div id="posBtmRight">
        <offcanvasComp />
      </div>


      
    </div>      
  </template>
  
  <script>
  import ButtonComp from './ButtonComp.vue';
  import offcanvasComp from './offcanvasComp.vue'
  
  export default {
    components : {
      ButtonComp,
      offcanvasComp
    }
  }
  
  </script>
  
  <style scoped>
  #landingPage{
    background-image: url("https://cdn-images.imagevenue.com/81/8f/87/ME17OVUR_o.jpg");
    background-repeat: no-repeat;
    background-size: cover;
    min-height: 100vh;
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
    border-image: fill 0 linear-gradient(rgba(0, 0, 0, 0.665), #030404a6);
  }
  
  #fontify{
    background: linear-gradient(to right,#48DD22, rgb(55, 255, 0));
    -webkit-background-clip: text;
    background-clip: text;
    -webkit-text-fill-color: transparent;
  }
  
  #btn{
    font-weight: 600;
  }

  #posBtmRight{
    position: absolute;
    right: 0%;
    bottom: 0%;
    margin-bottom: 10px;
    margin-right: 10px;
  }


  #jumbotron234{
    background:  rgba(62, 62, 62, 0.346) !important;
    width: 25%;
    -webkit-backdrop-filter: blur(10px);
    backdrop-filter: blur(10px);
    box-shadow: 2px 1px 30px 4px rgba(28, 28, 29, 0.34);
    border-radius: 50px;
  }
  
  
  #btn:hover{
    color: rgb(53, 230, 3);
    background-color: rgba(245, 245, 245, 0.214);
    -webkit-backdrop-filter: blur(2px);
    backdrop-filter: blur(2px);
    transform: scale(100.5%);
  }
  
  
  #rotate {
    --bg-color: #21212100;
    display: flex;
    justify-content: center;
  }
  
  #floatLikeInt{
    position: absolute;
    font-size: 20px;
    font-weight: 800;
    background: linear-gradient(to right,#ffffff, rgb(235, 235, 235));
    -webkit-background-clip: text;
    background-clip: text;
    -webkit-text-fill-color: transparent;
  }
  
  .rtpov {
    color: rgb(0, 0, 0);
    font-family: "Poppins", sans-serif;
    font-weight: 700;
    font-size: 50px;
    -webkit-box-sizing: content-box;
    box-sizing: content-box;
    height: 70px;
    display: -webkit-box;
    display: -ms-flexbox;
    display: flex;
  }
  
  #words {
    overflow: hidden;
    position: relative;
  }
  
  .word {
    display: block;
    height: 100%;
    padding-left: 6px;
    color: rgb(0, 216, 0);
    animation: spin_4991 11s infinite;
    font-weight: 700;
  }
  
  @keyframes spin_4991 {
    10% {
      -webkit-transform: translateY(-102%);
      transform: translateY(-102%);
    }
  
    25% {
      -webkit-transform: translateY(-100%);
      transform: translateY(-100%);
    }
  
    35% {
      -webkit-transform: translateY(-202%);
      transform: translateY(-202%);
    }
  
    50% {
      -webkit-transform: translateY(-200%);
      transform: translateY(-200%);
    }
  
    60% {
      -webkit-transform: translateY(-302%);
      transform: translateY(-302%);
    }
  
    75% {
      -webkit-transform: translateY(-300%);
      transform: translateY(-300%);
    }
  
    85% {
      -webkit-transform: translateY(-402%);
      transform: translateY(-402%);
    }
  
    100% {
      -webkit-transform: translateY(-400%);
      transform: translateY(-400%);
    }
  }
  
  h3 {
    margin: 40px 0 0;
  }
  
  ul {
    list-style-type: none;
    padding: 0;
  }
  
  li {
    display: inline-block;
    margin: 0 10px;
  }

  #landingPage{
    background-color: rgba(0, 0, 0, 0);
    min-height: 100vh;
    width: 100%;
  }

  a {
    color: #42b983;
  }
  
  #text{
    padding: 17px  0px;
    color: rgb(0, 0, 0);
    font-weight: bold;
  }


  #icw221{
    transform: scale(80%) translateY(190px);
    cursor: pointer;
    opacity: 0.3;
    transition: all 0.7s ease-in-out;
  }

  #icw221:hover{
    transform: scale(80%) translateY(185px);
    transition: all 0.7s ease-in-out;
  }
  
  /* Media queries */
  
  @media (max-width: 550px) {
    #iconBox{
      display: flex;
      flex-direction: column;
      padding-left: 120px !important;
    }
  
    #landingPage{
      padding-top: 70px !important;
    }

  .rtpov {
    color: rgb(0, 0, 0);
    font-family: "Poppins", sans-serif;
    font-weight: 700;
    font-size: 20px;
    -webkit-box-sizing: content-box;
    box-sizing: content-box;
    height: 30px;
    display: -webkit-box;
    display: -ms-flexbox;
    display: flex;
  }

  #icw221{
    display: none;
  }
  }
  
  
  @media (max-width: 450px) {
    #iconBox{
      display: flex;
      flex-direction: column;
      padding-left: 60px !important;
    }
  
    #landingPage{
      padding-top: 70px !important;
    }

    .rtpov {
    color: rgb(0, 0, 0);
    font-family: "Poppins", sans-serif;
    font-weight: 700;
    font-size: 30px;
    -webkit-box-sizing: content-box;
    box-sizing: content-box;
    height: 40px;
    display: -webkit-box;
    display: -ms-flexbox;
    display: flex;
  }

  #icw221{
    display: none;
  }
  }
  
  
  @media (max-width: 325px) {
    #iconBox{
      display: flex;
      flex-direction: column;
      padding-left: 20px !important;
    }
  
    #landingPage{
      padding-top: 70px !important;
    }
    .rtpov {
    color: rgb(0, 0, 0);
    font-family: "Poppins", sans-serif;
    font-weight: 700;
    font-size: 20px;
    -webkit-box-sizing: content-box;
    box-sizing: content-box;
    height: 30px;
    display: -webkit-box;
    display: -ms-flexbox;
    display: flex;
  }
  #icw221{
    display: none;
  }
  }
  
  </style>
  