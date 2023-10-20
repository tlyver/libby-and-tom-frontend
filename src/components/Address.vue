<script setup lang="ts">
    defineProps<{
        name: string
        address1: string
        address2?: string
        city: string
        state: string
        zip: string
    }>()
</script>

<template>
    <div>
        <h3>{{name }}</h3>
        <div>{{ address1 }}</div>
        <div v-if="address2">{{ address2 }}</div>
        <div>{{ city }}, {{ state }} {{ zip }}</div>
    </div>
</template>