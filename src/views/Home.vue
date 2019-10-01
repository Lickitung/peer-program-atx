<template>
  <div class="home">
    
    <home></home>
    <services></services>
    <about></about>
    <team></team>
    <contact></contact>

  </div>
</template>
<style>
</style>
<script>
// import Nav from '../components/Nav.vue'
import Home from '../components/Home.vue'
import Services from '../components/Services.vue'
import About from '../components/About.vue'
import Team from '../components/Team.vue'
import Contact from '../components/Contact.vue'

export default {
  components: {
    // Nav,
    Home,
    Services,
    About,
    Team,
    Contact
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