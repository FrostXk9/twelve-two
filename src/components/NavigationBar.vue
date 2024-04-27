<template>
    <nav class="navbar navbar-expand-lg" id="navbar">
      <div class="container-fluid">
        <button class="navbar-toggler border-0" type="button" data-bs-toggle="collapse" data-bs-target="#navbarTogglerDemo01" aria-controls="navbarTogglerDemo01" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon bg-white rounded-1"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarTogglerDemo01">
          <a class="navbar-brand" href="/">
            <img 
            src="https://cdn-thumbs.imagevenue.com/f7/b4/d5/ME17IVRQ_t.png" 
            alt="twelve_Two_logo" 
            id="imgLogo"
            loading="lazy"
            >
          </a>
          <ul class="navbar-nav ms-auto mb-lg-0 gap-4 mx-4">
            <li class="nav-item">
              <a class="nav-link text-decoration-none" id="nav" href="#home" data-nav>Home</a>
            </li>
            <li class="nav-item">
             <a class="nav-link text-decoration-none" id="nav"  href="#about" data-nav>About us</a>
            </li>
            <li class="nav-item">
              <a class="nav-link text-decoration-none" id="nav" href="#services" data-nav>Services</a>
            </li>
            <li class="nav-item">
              <a class="nav-link text-decoration-none" id="nav" href="#contact" data-nav>Contact us</a>
            </li>
          </ul>
        </div>
      </div>
    </nav>
  </template>
  
  <script>
  export default {
    methods : {
      fetchApiData : function(){
        this.$store.dispatch('fetchApiData')
      }
    },
  
    mounted(){
      this.fetchApiData()
    },
  }
  </script>
  
  <style scoped>
  
  #nav{
    font-weight: bold;
    color: rgb(20, 204, 54);
    transition: all 1s ease-in-out;
  }
  
  #navbar a.router-link-exact-active {
    text-decoration: none;
    color: rgb(20, 204, 54);
  }
  
  [data-nav] {
    color: rgb(20, 204, 54);
    font-family: inherit;
    font-weight: 800;
    cursor: pointer;
    position: relative;
    border: none;
    background: none;
    text-transform: uppercase;
    transition-timing-function: cubic-bezier(0.25, 0.8, 0.25, 1);
    transition-duration: 400ms;
    transition-property: color;
  }
  
  [data-nav]:focus,
  [data-nav]:hover {
    color: rgb(20, 204, 54);
  }
  
  [data-nav]:focus:after,
  [data-nav]:hover:after {
    width: 100%;
    left: 0%;
  }
  
  [data-nav]:after {
    content: "";
    pointer-events: none;
    bottom: -2px;
    left: 50%;
    position: absolute;
    width: 0%;
    height: 2px;
    background-color: rgb(20, 204, 54);
    transition-timing-function: cubic-bezier(0.25, 0.8, 0.25, 1);
    transition-duration: 400ms;
    transition-property: width, left;
  }
  
  #navbar{
    position: fixed;
    top: 0%;
    width: 100%;
    height: auto;
    z-index: 300;
    background-color: rgba(0, 0, 0, 0);
  }
  
  #imgLogo{
    height: 80px;
    width: 80px;
    border-radius: 50%;
    border: 5px solid rgb(20, 204, 54);
    background: #0d0d43;
    box-shadow: 1px 1px 10px 1px black;
  }
  
  @media (max-width: 992px) {
    #navbar{
      position: fixed;
      top: 0%;
      width: 100%;
      height: auto;
      z-index: 300;
      background-color: rgb(255, 255, 255);
    }
  }
  
      
  </style>