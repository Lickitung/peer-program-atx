<template>
  <div class="home">
    
    <home></home>
    <services></services>
    <about></about>
  </div>
</template>
<style>
</style>
<script>
// import Nav from '../components/Nav.vue'
import Home from '../components/Home.vue'
import Services from '../components/Services.vue'
import About from '../components/About.vue'

export default {
  components: {
    // Nav,
    Home,
    Services,
    About
  },
  data: function() {
    return {
      message: "Welcome to Vue.js!"
    };
  },
  created: function() {},
  methods: {}
};
</script>