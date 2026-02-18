<script setup lang="ts">
</script>

<template>
  <div
    class="
      overflow-hidden
      dark:bg-gray-800
      rounded-xl
      border border-gray-200 dark:border-gray-700
      relative
      shadow-xl
      hover:shadow-3xl hover:border-gray-900
      group transition-all duration-300
      h-full
    "
  >
   <!-- Default slot for content without named slots -->
    <div class="relative" v-if="$slots.default">
      <slot />
    </div>

    <!-- images  -->
    <div v-if="$slots.img" class="overflow-hidden relative h-32 w-full p-4 flex items-center justify-center">  <slot name="img" /> </div>

    <div class="flex flex-col justify-between">
        
      <!-- Cart Header -->
      <div v-if="$slots.header"
        class="
          p-4
          border-b border-gray-200 dark:border-gray-700 border-dashed text-xl
        "
      >
        <slot name="header" />
      </div>

      <!-- Cart Body -->
      <div v-if="$slots.body" class="p-4 flex flex-col justify-end">
        <slot name="body" />
      </div>

    </div>
   
  </div>
</template>
