<script >
import HelloWorld from './components/HelloWorld.vue'
import AppTitle from './components/AppTitle.vue'
import TheWelcome from './components/TheWelcome.vue'
import AppHero from './components/AppHero.vue'

export default {
  name: "App",
  components: {
    AppTitle,
    AppHero,
  }
}
</script>



<template>
  <AppHero />
<AppTitle />
  
</template>

<style scoped>

</style>
