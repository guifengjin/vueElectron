<template>
  <div class="home">
    <h1>HOME - PAGE</h1>
    <button @click="goAbout">GO ABOUT***</button>
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
