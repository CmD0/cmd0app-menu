<script setup lang="ts">
import projects from './projects';
import ProjectItem from './ProjectItem.vue';
</script>

<template>
    <ul id="projects">
        <ProjectItem v-for="project in projects" :key="project.name" :project="project" />
    </ul>
</template>

<style scoped>
.project-item {
    margin: 1em;
    margin-left: 0;
    padding: 1em;
    border: 2px solid var(--vt-c-divider-dark-1);
    border-radius: 10px;
}
</style>