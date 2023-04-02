<script setup lang="ts">
import ProjectsList from '@/components/Projects/ProjectsList.vue';
</script>

<template>
  <header>
    <h1>Welcome to cmd0app.com!</h1>
    <h2>CmD0_'s web project hub</h2>
  </header>

  <main>
    <h2>My Projects:</h2>
    <ProjectsList />
  </main>
</template>

<style scoped>
header {
  line-height: 1.5;
}

#projects {
  list-style: none;
  padding: 0;
  margin: 0;
  margin-top: 1rem;
}

.project-item {
  margin: 0 0 1rem;
}

.project-link {
  text-decoration: none;
  font-size: large;
  font-weight: 600;
}

.logo {
  display: block;
  margin: 0 auto 2rem;
}

@media (min-width: 1024px) {
  header {
    display: flex;
    flex-direction: column;
    place-items: center;
    padding-right: calc(var(--section-gap) / 2);
  }
}
</style>
