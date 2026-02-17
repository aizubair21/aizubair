<script setup lang="ts">
</script>

<template>
  <div
    class="
      group
      bg-white dark:bg-gray-800
      rounded-sm
      border border-gray-200 dark:border-gray-700
      overflow-hidden
      relative
      hover:shadow-3xl hover:border-gray-900
      group transition-all duration-300
    "
  >
   <!-- Default slot for content without named slots -->
    <div class="relative" v-if="$slots.default">
      <slot />
    </div>

    <!-- images  -->
    <div v-if="$slots.img" class="overflow-hidden relative h-32 w-full p-4 flex items-center justify-center">  <slot name="img" /> </div>


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
    <div v-if="$slots.body" class="p-4 flex flex-col justify-end flex-1">
      <slot name="body" />
    </div>

   
  </div>
</template>
