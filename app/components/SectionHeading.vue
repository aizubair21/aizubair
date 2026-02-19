<script lang="ts" setup>
const {heading, subHeading} = defineProps({heading:String, subHeading:String })

</script>

<template>
  <div class="text-center mb-16">
    <h2 class="text-3xl sm:text-4xl md:text-5xl font-bold mb-4">
      <span class="uppercase bg-gradient-to-r from-purple-600 via-blue-600 to-pink-600 bg-clip-text text-transparent dark:from-purple-400 dark:via-blue-400 dark:to-pink-400">
        {{ heading }}
      </span>
    </h2>
    <p class="text-lg text-gray-600 dark:text-gray-300 max-w-2xl mx-auto">
      {{ subHeading }}
    </p>
  </div>
</template>

<style lang="postcss" scoped>
    
</style>
