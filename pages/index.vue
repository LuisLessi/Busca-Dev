<template>
  <div>

    <Slider />

    <AboutUs />

    <OurService />

    <div class="py-5">
      <div class="container">
        <div class="row">
          <div class="col-md-8">
            <h1 class="main-heading">
              if you have any queries ?
            </h1>
            <h4>Please Reach out us at luisadsfatec@hotmail.com <br> or (16) 99792-9960</h4>
          </div>
          <div class="col-md-4 text-center my-auto">
            <NuxtLink to="/contact" class="px-5 py-2 btn btn-primary">Contact Us</NuxtLink>
          </div>
        </div>
      </div>
    </div>

  </div>
</template>

<script>
import Slider from '../components/slider.vue'
import AboutUs from '../components/AboutUs.vue'
import OurService from '../components/OurService.vue'

export default {
  name: 'IndexPage',
  components: {
    Slider,
    AboutUs,
    OurService
  },
  head() {
    return {
      title: 'Home',

    }
  }
}
</script>

