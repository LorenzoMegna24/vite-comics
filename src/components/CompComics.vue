<script>
  export default{
    name: "CompComics",
    props: ['DettaglioComic']
   }
</script>

<template>
  <div class="card">
    <img :src="DettaglioComic.thumb" alt="">
    <h3>{{ DettaglioComic.series }}</h3>
    <span>{{ DettaglioComic.type }}</span>
    <span>{{ DettaglioComic.price }}</span>
  </div>

</template>

<style lang="scss" scoped >

</style>