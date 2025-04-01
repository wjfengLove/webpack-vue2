<!-- src/App.vue -->
<template>
  <div class="greeting">{{ message }}</div>
</template>

<script>
export default {
  data() {
    return {
      message: 'Hello Vue 2!'
    }
  }
}
</script>

<style scoped>
.greeting {
  color: #42b983;
}
</style>