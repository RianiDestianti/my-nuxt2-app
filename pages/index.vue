<template>
  <div>
    <Hero />
    <Features />
    <About />
    <Cta />
    <Footer />
  </div>
</template>

<script>
import Hero from '~/components/Hero.vue'
import Features from '~/components/Features.vue'
import About from '~/components/About.vue'
import Cta from '~/components/Cta.vue'
import Footer from '~/components/Footer.vue'

export default {
  name: 'LandingPage',
  components: {
    Hero,
    Features,
    About,
    Cta,
    Footer
  }
}
</script>
