<template>
  <div>
    <div class="py-4 bg-warning">
      <div class="container text-center">
        <h3>Our Services</h3>
      </div>
    </div>
    <OurService />
</div>
</template>

<script>
import OurService from '~/components/OurService.vue';
export default {
  name:'services',
  components:{
    OurService
  },
  head() {
      return {
        title: 'Services',

      }
    }
}
</script>

