<script lang="ts" setup>

const { src, clas } = defineProps({src:String, clas:String});

</script>

<template>
    <img :src class="group-hover:scale-110 group-hover:-rotate-15 transition-all duration-300" :class="clas"/>
</template>

<style lang="postcss" scoped>
    
</style>
