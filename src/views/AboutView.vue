<template>
  <div class="about">
    <h1>This is an about page</h1>
    <fubar/>
  </div>
</template>
<script>
import Fubar from '@/components/fubar.vue'

export default {
  name: 'HomeView',
  components: {
    Fubar
   
  }
}
</script>
