<template>
  <div class="container">
    <h1>My Portfolio</h1>
    <div class="project-grid">
      <ProjectCard
        title="Weather App"
        description="A simple Vue app that fetches weather data."
        image="https://via.placeholder.com/300"
        link="https://yourprojectlink.com"
      />
      <ProjectCard
        title="To-Do List"
        description="A to-do list built with Vue 3 and local storage."
        image="https://via.placeholder.com/300"
        link="https://yourprojectlink.com"
      />
    </div>
  </div>
</template>

<script setup>
import ProjectCard from './components/ProjectCard.vue'
import './style.css'
</script>
