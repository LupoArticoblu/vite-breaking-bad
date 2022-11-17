<script>
  export default {
    name: 'HeaderApp',
    props:{
      title: string
    }
  }
</script>

<template>
  
<div class="container py-3 text-center">
  <h1>{{title}}</h1>
</div>

</template>

<style lang="scss" scoped>

</style>