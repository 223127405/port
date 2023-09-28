<template>
  <div class="home-view">
    <h2>Welcome to My Portfolio</h2>
    <p>Welcome to my portfolio homepage.</p>
    <router-link to="/about" class="learn-more-link">Learn more about me</router-link>
  </div>
</template>

<script>
export default {
  name: 'HomeView',
}
</script>

<style scoped>
.home-view {
  text-align: center;
  padding: 20px;
  background-color: #fff; /* Change this line to set the background color */
  border-radius: 5px;
  box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
  color: #333;
}

.learn-more-link {
  display: inline-block;
  margin-top: 10px;
  padding: 10px 20px;
  background-color: #007BFF;
  color: white;
  text-decoration: none;
  border-radius: 5px;
  font-size: 16px;
  transition: background-color 0.3s;
}

.learn-more-link:hover {
  background-color: #0056b3;
}
</style>
