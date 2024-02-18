<template>
  <div id="home">
    <HelloWorld />
  </div>

  <div id="about">
    <AboutComp />
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue';
import AboutComp from '../components/AboutComp.vue';

export default {
  name: 'HomeView',
  components: {
    HelloWorld,
    AboutComp
  }
}
</script>
<style>
::-webkit-scrollbar{
  width: 0px;
}
</style>
