<template>
  <div id="app">
    <TackleboxDemo></TackleboxDemo>
  </div>
</template>

<script>
import TackleboxDemo from './components/TackleboxDemo.vue'

export default {
  name: 'App',
  components: {
    TackleboxDemo
  }
}
</script>

<style lang="sass">
@import "@narrative.io/tackle-box/src/styles/global/_fonts"
@import "@narrative.io/tackle-box/src/styles/global/_colors"
@import "@narrative.io/tackle-box/src/styles/global/_color-helpers"
@import "@narrative.io/tackle-box/src/styles/global/_typography"

#app 
	font-family: "Euclid Circular A"
</style>
