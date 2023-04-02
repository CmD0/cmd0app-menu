<script setup lang="ts">
import ProjectsList from '@/components/Projects/ProjectsList.vue';
</script>

<template>
  <header>
    <h1>Welcome to cmd0app.com!</h1>
    <h2><a href="https://github.com/CmD0">CmD0_'s</a> web projects hub</h2>
  </header>

  <main>
    <h2>Hosted Projects:</h2>
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
