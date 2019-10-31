<template>
  <div>
    <h1 class="cyan">Oh my {{ two }} page</h1>
  </div>
</template>

<script>
export default {
  asyncData (context) {
    return { two: 'two' }
  }
}
</script>

<style>
.cyan {
  color: cyan;
}
</style>
