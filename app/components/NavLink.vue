<script setup lang="ts">
interface Props {
  href?: string
  active?: boolean
}

withDefaults(defineProps<Props>(), {
  href: '#',
  active: false
})
</script>

<template>
  <NuxtLink
    :to="href"
    class="
      text-sm group text-gray-700 dark:text-gray-300
      hover:text-gray-900 dark:hover:text-white
      transition-colors duration-300
    "
    :class="{ 'text-gray-900 dark:text-white': active }"
  >
    <span class="inline-flex justify-between items-center gap-2 relative overflow-hidden">
      <slot />
      <!-- Arrow icon that slides from right to left on hover -->
      <span
        class="
          block
          transition-transform duration-300 ease-in-out
          group-hover:translate-x-0.5 group-hover:opacity-100
        "
      >
        <svg
          xmlns="http://www.w3.org/2000/svg"
          fill="none"
          viewBox="0 0 24 24"
          stroke-width="2"
          stroke="currentColor"
          class="w-4 h-4"
        >
          <path
            stroke-linecap="round"
            stroke-linejoin="round"
            d="M13.5 4.5L21 12m0 0l-7.5 7.5M21 12H3"
          />
        </svg>
      </span>
    </span>
  </NuxtLink>
</template>
