<template>
  <div>
    <div class="py-4 bg-warning">
      <div class="container text-center">
        <h1>About Us</h1>
      </div>
    </div>
    <AboutUs/>
  </div>
</template>

<script>
import AboutUs from '~/components/AboutUs.vue';

export default {
name: 'about',
components:{
  AboutUs
},
head() {
      return {
        title: 'About Us',

      }
    }
}
</script>

<style>

</style>
