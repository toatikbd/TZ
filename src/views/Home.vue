<template>
  <div class="home">

    <Loginld/>
    <!-- <SingIn/> -->
  </div>
</template>

<script>
// @ is an alias to /src
import Loginld from '@/components/Loginld.vue';
// import SingIn from '@/components/SingIn.vue';

export default {
  name: 'Home',
  components: {
    Loginld,
    // SingIn
  }
}
</script>
