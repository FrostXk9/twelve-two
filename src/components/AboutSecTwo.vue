<template>
 <div class="row featurette">
      <div class="col-md-7">
        <h2 class="text-start featurette-heading fw-normal lh-1">First featurette heading. <span class="text-body-secondary">Itll blow your mind.</span></h2>
        <p class="lead text-start">Twelve two is dedicated to empowering individuals on their financial journey through coaching.Our mission is to demystify personal finance, fostering confidence and success. Guided by a commitment to holistic financial wellness, we provide tailored coaching services, equipping clients with practical tools and strategies for spending plans,investing,and debt elimination.At Twelve Two, we belive in a collaborative approach, working alongside you to transform financial goals into achievable realities.Let us be your partner in navigating the path to financial well-being</p>
      </div>
      <div class="col-md-5" id="container">
        <img class="bd-placeholder-img bd-placeholder-img-lg featurette-image img-fluid mx-auto" width="500" height="500" src="https://cdn-images.imagevenue.com/77/9c/79/ME17OWCE_o.jpg" role="img" id="img"/>
      </div>
    </div>

    <hr class="featurette-divider">

    <div class="row featurette">
      <div class="col-md-7 order-md-2">
        <h2 class="featurette-heading fw-normal lh-1">Oh yeah, its that good. <span class="text-body-secondary">See for yourself.</span></h2>
        <p class="lead">Another featurette? Of course. More placeholder content here to give you an idea of how this layout would work with some actual real-world content in place.</p>
      </div>
      <div class="col-md-5" id="container">
        <img class="bd-placeholder-img bd-placeholder-img-lg featurette-image img-fluid mx-auto" width="500" height="500" src="https://cdn-images.imagevenue.com/2b/ac/f2/ME17OWE5_o.jpg" role="img" id="img"/>
      </div>
    </div>

    <hr class="featurette-divider">

    <div class="row featurette">
      <div class="col-md-7">
        <h2 class="featurette-heading fw-normal lh-1">And lastly, this one. <span class="text-body-secondary">Checkmate.</span></h2>
        <p class="lead">And yes, this is the last block of representative placeholder content. Again, not really intended to be actually read, simply here to give you a better view of what this would look like with some actual content. Your content.</p>
      </div>
      <div class="col-md-5" id="container">
        <img class="bd-placeholder-img bd-placeholder-img-lg featurette-image img-fluid mx-auto" width="500" height="500" src="https://cdn-images.imagevenue.com/fd/f2/b7/ME17OWEC_o.jpg" role="img" id="img"/>
      </div>
    </div>
</template>
<script>
export default {
    
}
</script>
<style>
#container {
  overflow: hidden;
}
#container #img {
  display: block;
  transition: transform 1s;
}
#container:hover #img {
  transform: scale(1.3);
  transform-origin: 50% 50%;
}
</style>