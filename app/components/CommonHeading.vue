<script lang="ts" setup>
const {heading, subHeading} = defineProps({heading:String, subHeading:String })

</script>

<template>
    <div class="
      text-xl
      uppercase
      text-gray-900
      dark:text-gray-400
    "> {{ heading }} </div>
    <AppContent > {{ subHeading }} </AppContent>
</template>

<style lang="postcss" scoped>
    
</style>
