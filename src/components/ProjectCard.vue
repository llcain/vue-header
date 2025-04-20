<template>
  <div class="card">
    <img :src="image" alt="project image" />
    <h3>{{ title }}</h3>
    <p>{{ description }}</p>
    <a :href="link" target="_blank">View Project</a>
  </div>
</template>

<script setup>
defineProps(['title', 'description', 'image', 'link'])
</script>

<style scoped>
.card {
  background: white;
  padding: 1rem;
  border-radius: 8px;
  width: 280px;
  box-shadow: 0 2px 8px rgba(0,0,0,0.1);
  text-align: center;
}
.card img {
  max-width: 100%;
  border-radius: 4px;
}
.card a {
  color: #42b883;
  text-decoration: none;
  font-weight: bold;
}
</style>
