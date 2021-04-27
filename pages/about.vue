<template>
  <div class="about">
    <h1>About</h1>
  </div>
</template>

<script>
  export default {
    name: 'AboutPage',
    transition: {
      name: 'page',
      mode: ''
    },
    mounted() {
      console.log('About page mounted')
    },
    activated() {
      console.log('About page activated')
    }
  }
</script>

<style scoped>
.about {
  display: flex;
  justify-content: center;
  align-items: center;
  background: green;
  width: 100%;
  min-height: 100vh;
}
</style>
