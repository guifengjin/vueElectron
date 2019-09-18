<template>
  <div class="about">
    <h1>ABOUT PAGE</h1>
    <button @click="goHome">GO HOME***</button>
  </div>
</template>

<script>
export default {
  methods: {
    goHome() {
      this.$router.push({
        path: '/'
      })
    }
  }
}
</script>
