<script setup lang="ts">
    defineProps<{
        title?: string
        subtitle?: string
    }>()
</script>

<template>
    <div>
        <h2>{{ title }}</h2>
        <div>{{  subtitle }}</div>
    </div>
</template>