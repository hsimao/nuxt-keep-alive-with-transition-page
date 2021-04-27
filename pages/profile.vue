<template>
  <div class="profile">
    <h1>Profile</h1>
  </div>
</template>

<script>
  export default {
    name: 'ProfilePage',
    transition: {
      name: 'page',
      mode: ''
    },
    mounted() {
      console.log('Profile page mounted')
    },
    activated() {
      console.log('Profile page activated')
    }
  }
</script>

<style scoped>
.profile {
  display: flex;
  justify-content: center;
  align-items: center;
  background: blue;
  width: 100%;
  min-height: 100vh;
}
</style>
