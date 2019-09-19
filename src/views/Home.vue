<template>
  <div class="home">
    <h1>HOME - PAGE</h1>
    <el-button @click="goAbout">GO ABOUT</el-button>
  </div>
</template>

<script>

export default {
  name: 'home',
  methods: {
    goAbout() {
      this.$router.push({
        path: '/about'
      })
    },
  }
}
</script>
