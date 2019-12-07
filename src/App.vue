<template>
  <div id="app">
    <Splash />
    <Manifesto />
    <SocialProof />
    <TeaserContent />
    <Testimonial />
    <Cta />
    <About />
  </div>
</template>

<script>
import About from './components/about';
import Cta from './components/cta';
import Manifesto from './components/manifesto';
import SocialProof from './components/socialProof';
import Splash from './components/splash';
import TeaserContent from './components/teaserContent';
import Testimonial from './components/testimonial';

export default {
  name: 'app',
  components: {
    TeaserContent,
    Splash,
    SocialProof,
    Manifesto,
    Testimonial,
    Cta,
    About,
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
