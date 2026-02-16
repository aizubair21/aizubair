<script setup lang="ts">
interface Props {
  variant?: 'primary' | 'secondary'
  type?: 'button' | 'submit' | 'reset'
}

const props = withDefaults(defineProps<Props>(), {
  variant: 'primary',
  type: 'button'
})
</script>

<template>
  <button
    :type="type"
    class="
      inline-flex items-center justify-center
      px-4 py-2
      font-semibold text-xs uppercase tracking-wide
      rounded-sm
      transition-all duration-300 ease-in-out
      hover:opacity-80 hover:shadow-md
      disabled:opacity-50 disabled:cursor-not-allowed
      focus:outline-none focus:ring-2 focus:ring-offset-2
      bg-gray-900 text-white
      dark:bg-white dark:text-gray-900
    "
    :class="{
      'bg-gradient-to-r from-purple-500 to-pink-500 text-white hover:from-purple-600 hover:to-pink-600': variant === 'primary',
      'bg-gray-500 text-white hover:bg-gray-600': variant === 'secondary'
    }"
  >
    <slot />
  </button>
</template>
