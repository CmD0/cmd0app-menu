<script setup lang="ts">
import projects from './projects';
import ProjectItem from './ProjectItem.vue';
</script>

<template>
    <ul id="projects">
        <ProjectItem v-for="project in projects" :key="project.name" :project="project" />
    </ul>
</template>