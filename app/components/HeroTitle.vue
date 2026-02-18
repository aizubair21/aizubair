<script lang="ts" setup>
const { title } = defineProps({title:String})
</script>

<template>
    <h1 class="text-4xl sm:text-5xl md:text-6xl lg:text-7xl font-bold leading-tight mb-6">
        <span class="bg-gradient-to-r from-purple-600 via-blue-600 to-pink-600 bg-clip-text text-transparent dark:from-purple-400 dark:via-blue-400 dark:to-pink-400">
        {{ title }}
        </span>
    </h1>
</template>

<style lang="postcss" scoped>
    
</style>
