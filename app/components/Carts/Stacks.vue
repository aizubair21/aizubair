<script lang="ts" setup>
const { stacks } = defineProps({stacks:Object})
</script>

<template>
    <Flex class="flex-wrap gap-4">
        <Cart v-for="(stack, key) in stacks" :key="key" class="w-[150px] bg-transparent">
        <NuxtLink class="group relative text-center">
            <Img :src="stack.icon"  class="mx-auto h-24 p-4 animate-pulse cursor-pointer" :style="`animation-duration: ${key+1}s`" />
            <Content class="transition-all duration-200"> {{ stack.name }} </Content>
        </NuxtLink>
        </Cart>
    </Flex>
</template>

<style lang="postcss" scoped>
    
</style>
