<script setup lang="ts">
    defineProps<{
        attire?: string
        address?: string
        // name: string
    }>()
</script>

<template>
    <div>
        <i>
            <slot name="icon"></slot>
        </i>
        <slot></slot>
    </div>
</template>