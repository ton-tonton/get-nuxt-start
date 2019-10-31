<template>
  <div>
    <h1 class="cyan">Oh my {{ one }} page</h1>
  </div>
</template>

<script>
export default {
  asyncData (context) {
    return { one: 'one' }
  }
}
</script>

<style>
.cyan {
  color: cyan;
}
</style>
