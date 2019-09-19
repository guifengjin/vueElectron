<template>
  <div class="about">
    <h1>ABOUT PAGE</h1>
    <el-button @click="goHome">GO HOME</el-button>
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
