<script>
import AppTitle from './components/AppTitle.vue';
import AppHero from './components/AppHero.vue';
export default {
  components: {
    AppTitle,
    AppHero
  }
}
</script>

<template>
  <AppTitle/>
  <AppHero/>
</template>

<style scoped>
  h1 {
    color: rgb(247, 8, 139);
  }
</style>
