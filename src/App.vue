<script>
  import CompHeader from './components/CompHeader.vue'
  import CompMain from './components/CompMain.vue'

  export default{
    name: "App",
    components: {
      CompHeader,
      CompMain,
    }
  }
</script>

<template>
  <CompHeader/>
  <CompMain/>
</template>

<style lang="scss">
  @use './style/main.scss' as *;

</style>
