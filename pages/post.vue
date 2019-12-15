<template>
  <div class="container">
    <article>
      <h1 class="title">This is an article heading</h1>
      <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec facilisis viverra eros at maximus. Mauris efficitur nunc in aliquam finibus. Proin lobortis dictum congue. Nunc ac erat vitae ipsum fringilla volutpat. Suspendisse eu metus vel lacus dictum viverra. Nunc dapibus risus in sodales malesuada. In at mollis arcu, eget blandit lacus. Nulla sem turpis, tristique et odio sed, feugiat mattis ex. Nullam dignissim tristique dolor eget ornare.</p>
    </article>
  </div>
</template>

<script>

export default {}

</script>

<style scoped>
  .container{
    display: flex;
    justify-content: space-between;
    line-height: 1.5;
  }

  article * {
    margin-bottom: 1rem;
  }

  aside{
    min-width: 280px;
    min-width: 280px;
    padding-left: 2rem;
  }

  .title{
    font-size: 2rem;
  }
</style>
