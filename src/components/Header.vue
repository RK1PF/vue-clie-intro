<template>
  <nav>
    <router-link to="Home">Home</router-link> |
    <router-link to="About">About</router-link>
    <router-view />
  </nav>
</template>

<script>
export default {};
</script>
<style>
a {
  padding: 1em;
}
</style>
