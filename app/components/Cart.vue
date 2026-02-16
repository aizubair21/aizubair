<script setup lang="ts">
</script>

<template>
  <div
    class="
      bg-white dark:bg-gray-800
      rounded-sm
      border border-gray-200 dark:border-gray-700
      overflow-hidden
    "
  >
   <!-- Default slot for content without named slots -->
    <div class="relative" v-if="$slots.default">
      <slot />
    </div>


    <!-- Cart Header -->
    <div v-if="$slots.header"
      class="
        p-3 md:px-4 
        border-b border-gray-200 dark:border-gray-700 border-dashed text-xl leading-relaxed
      "
    >
      <slot name="header" />
    </div>

    <!-- Cart Body -->
    <div v-if="$slots.body" class="p-3 md:px-4 ">
      <slot name="body" />
    </div>

   
  </div>
</template>
