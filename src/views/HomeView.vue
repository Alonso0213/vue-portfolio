<template>
  <div class="home">
    
<fubar/>
  </div>
</template>

<script>
import Fubar from '@/components/fubar.vue'
import navBar from '../components/navBar.vue'

export default {
  name: 'HomeView',
  components: {
    navBar,
    Fubar,
   
  }
}
</script>
