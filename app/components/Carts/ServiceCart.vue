<script lang="ts" setup>
    const { services } = defineProps({services:Object})
</script>

<template>
    <div v-for="serv in services.serv" class="group relative inset-2 ">
      <div class="absolute -inset-1 bg-gradient-to-r rounded-2xl blur opacity-25 group-hover:opacity-75 transition duration-500" :class="serv.color"></div>
      <div class="relative p-8 flex flex-col bg-white shadow-xl dark:bg-gray-900 rounded-2xl hover:shadow-2xl transition-all duration-300" style="height:stretch">
        <!-- Icon -->
        <div class="text-5xl mb-4">{{ serv.icon }}</div>
        
        <!-- Title -->
        <Heading>
          {{ serv.name }}
        </Heading>
        
        <!-- Description -->
        <p class="flex-1 text-gray-600 dark:text-gray-300 mb-6 leading-relaxed">
          {{ serv.description }}
        </p>
        
        <!-- Tags -->
        <div class="flex flex-wrap gap-2 mb-6">
          <span 
            v-for="tag in serv.tags" 
            :key="tag"
            class="px-3 py-1 text-xs font-medium bg-gray-100 dark:bg-gray-800 text-gray-600 dark:text-gray-300 rounded-full"
          >
            {{ tag }}
          </span>
        </div>
        
        <!-- CTA -->
        <NavLink :href="serv.url.href" class="inline-flex items-center gap-2 text-purple-500 font-semibold group-hover:gap-3 transition-all">
          {{ serv.url.text }}
        </NavLink>
      </div>
    </div>
</template>

<style lang="postcss" scoped>
    
</style>
