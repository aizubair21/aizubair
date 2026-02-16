<script lang="ts" setup>
    const {title, position, color} = defineProps({title:String, position:String, color:String})
</script>

<template>
    <Content class="absolute px-2 rounded-sm text-xs z-2" :class="[position, color]">{{title}}</Content>
</template>

<style lang="postcss" scoped>
    
</style>
