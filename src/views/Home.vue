<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/loterias.png">
    <HomeComponent msg="Esta é uma versão Beta do sistema"/>
  </div>
</template>

<script>
// @ is an alias to /src
import HomeComponent from '@/components/HomeComponent.vue'

export default {
  name: 'home',
  components: {
    HomeComponent
  }
}
</script>
