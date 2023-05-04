<script>
   export default{
        name: "CompHeader",
   }
</script>

<template>
  <header>
    <nav>
      <div class="logo">
        <a href="/"><img src="../../public/img/dc-logo.png" alt=""></a>
      </div>
      <div>
        <ul>
          <li><a href="/">characters</a></li>
          <li class="active"><a href="/">comics</a></li>
          <li><a href="/">movies</a></li>
          <li><a href="/">tv</a></li>
          <li><a href="/">games</a></li>
          <li><a href="/">collectibles</a></li>
          <li><a href="/">videos</a></li>
          <li><a href="/">fans</a></li>
          <li><a href="/">news</a></li>
          <li><a href="/">shop</a></li>
        </ul>
      </div>
    </nav>
  </header>
  
</template>

<style lang="scss" scoped>
.active{
  color: rgb(45, 130, 233);
  border-bottom: solid 4px rgb(45, 130, 233);
}
</style>
