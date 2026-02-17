<script lang="ts" setup>
const {min = '250px', max = '300px', gap = '10px'} = defineProps({min:String, gap:String, max:String})
</script>

<template>
    <div class="my-4 justify-center" :style="`display:grid; justify-content:center; grid-template-columns:repeat(auto-fill, minmax(${min}, ${max})); grid-gap: ${gap}`">
        <slot />
    </div>
</template>

<style lang="postcss" scoped>
    
</style>
