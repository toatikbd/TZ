<template>
  <div class="dashboard"> 
    <TopBar/>
    <LeftSidebar/>
    
  </div>
</template>
<script>

import TopBar from '@/components/TopBar.vue';
import LeftSidebar from '@/components/LeftSidebar.vue'

export default {
  name: 'Dashboard',
  components: {
    TopBar,
    LeftSidebar
  }
  
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>


</style>
