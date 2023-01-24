
<template>
  <header>
    <nav>
      <RouterLink to="/" class="home">Home</RouterLink> |
      <RouterLink to="/about" class="about">About</RouterLink>
    </nav>
  </header>
  <RouterView />
</template>

<script lang="ts">
  import { RouterLink, RouterView } from 'vue-router'
  export default {
    name: 'App'
  }
</script>


<style scoped>

</style>
