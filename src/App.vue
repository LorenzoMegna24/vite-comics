<script>
  import CompHeader from './components/CompHeader.vue'

  export default{
    name: "App",
    components: {
      CompHeader,
    }
  }
</script>

<template>
  <CompHeader/>
</template>

<style lang="scss">
  @use './style/main.scss' as *;

</style>
