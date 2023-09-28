<template>
  <header>
    <nav>
      <router-link to="/" class="nav-link">Home</router-link>
      <router-link to="/about" class="nav-link">About</router-link>
      <router-link to="/portfolio" class="nav-link">Portfolio</router-link>
      <router-link to="/contact" class="nav-link">Contact</router-link>
    </nav>
  </header>
</template>

<script>
export default {
  name: 'HeaderView',
};
</script>

<style scoped>
/* adding styles in the hearder component */
header {
  background-color: #007BFF;
  color: white;
  padding: 10px;
  text-align: center;
}

.nav-link {
  color: white;
  text-decoration: none;
  margin: 0 10px;
  font-size: 18px;
}
</style>
