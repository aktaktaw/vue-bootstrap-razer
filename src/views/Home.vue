<template>
  <div class="bg-primary">
    <Navbar/>
    <Carousel/>

  </div>
</template>

<script>
// @ is an alias to /src
//import HelloWorld from '@/components/HelloWorld.vue'
import Navbar from '@/components/Navbar'
import Carousel from '@/components/Carousel'

export default {
  name: 'Home',
  components: {
    Navbar,
    Carousel,

  }
}
</script>
