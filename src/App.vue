<script>
  import CompHeader from './components/CompHeader.vue'
  import CompMain from './components/CompMain.vue'
  import CompFooter from './components/CompFooter.vue'


  export default{
    name: "App",
    components: {
      CompHeader,
      CompMain,
      CompFooter
    }
  }
</script>

<template>
  <CompHeader/>
  <CompMain/>
  <CompFooter/>
</template>

<style lang="scss">
  @use './style/main.scss' as *;

</style>
