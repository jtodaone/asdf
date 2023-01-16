<script>

</script>

<template>
  <div class="menubar">
    <RouterLink to="/">Home</RouterLink>
    <RouterLink to="/about">About</RouterLink>
  </div>
  <RouterView />
</template>

<style scoped>
  .menubar {
    display: flex;
    flex-direction: row;
    gap: 1em;
  }
</style>
