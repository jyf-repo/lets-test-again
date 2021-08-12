<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png" style="width:40%">
    <HomeComponent msg="Let's test again"/>
  </div>
</template>

<script>
// @ is an alias to /src
import HomeComponent from '@/components/HomeComponent.vue'

export default {
  name: 'Home',
  components: {
    HomeComponent
  }
}
</script>
