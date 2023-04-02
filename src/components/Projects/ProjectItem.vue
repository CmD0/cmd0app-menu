<script setup lang="ts">
defineProps({
    project: {
        type: Object,
        required: true
    }
});
</script>

<template>
    <li class="project-item">
        <a :href="project.URL" class="project-link">{{ project.name }}</a>
        <p>{{ project.description }}</p>
    </li>
</template>