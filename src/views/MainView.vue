<template>
  <div id="home">

    <HelloWorld />

  </div>

  <div id="about">

    <AboutComp />

  </div>

  <!-- <div id="ourTimeLine">

    <TimelineComp />

  </div> -->

  <div id="contact">

    <ContactComp />

  </div>
</template>

<script>
import HelloWorld from '../components/HelloWorld.vue';
import AboutComp from '../components/AboutComp.vue';
import TimelineComp from '../components/TimelineComp.vue';
import ContactComp from '../components/ContactComp.vue';;

export default {
  name: 'HomeView',
  components: {
    HelloWorld,
    AboutComp,
    TimelineComp,
    ContactComp,
  }
}
</script>
<style>
::-webkit-scrollbar{
  width: 0px;
}

#contact{
  background-image: url('https://cdn-images.imagevenue.com/a3/1f/65/ME17PSZF_o.jpg');
  background-repeat: no-repeat;
  background-size: cover;
  border-image: fill 0 linear-gradient(rgb(0, 0, 0), rgba(0, 0, 0, 0.838) 70%);
  min-height: 105vh;
  display: flex;
  justify-content: center;
  align-items: center;
}
</style>
