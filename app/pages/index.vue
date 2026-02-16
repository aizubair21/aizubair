<script setup>
import {ref} from 'vue';

definePageMeta({
    
})      

useSeoMeta({
  title: 'ApexMe - Digital Solutions for Business Growth',
  description: 'Professional developer portfolio showcasing custom web applications, mobile solutions, and digital transformation services.'
})

const hero = ref({
  title: 'Building Digital Solutions That Drive Business Growth',
  subtitle: 'I transform complex challenges into elegant, high-performing applications that help your business succeed in the digital landscape.',
  ctaPrimary: 'View Portfolio',
  ctaSecondary: 'Start a Project',
  trust:
  {
    title:'Trusted by businesses worldwide',
    indicator: ['Web Development', 'Mobile Apps', 'Cloud Solutions']
  }
})

const stack = ref(
  {
    title: 'Tech Stack',
    subtitle: 'The powerful tools I use to build modern web applications',
    tall: [
      {
        name: 'TailwindCSS',
        icon: '🌀',
        color: 'from-cyan-400 to-blue-500',
        description: 'Utility-first CSS framework',
        url: {
          href:'',
          text :'Learn More',
        }
      },
      {
        name: 'Alpine.js',
        icon: '🏔️',
        color: 'from-orange-400 to-red-500',
        description: 'Lightweight JavaScript framework',
        url: {
          href:'',
          text :'Learn More',
        }
      },
      {
        name: 'Livewire',
        icon: '⚡',
        color: 'from-yellow-400 to-orange-500',
        description: 'Full-stack framework for Laravel',
        url: {
          href:'',
          text :'Learn More',
        }
      },
      {
        name: 'Laravel',
        icon: '🔥',
        color: 'from-red-500 to-pink-600',
        description: 'PHP framework for web artisans',
        url: {
          href:'',
          text :'Learn More',
        }
      }
    ]
  }
);

const services = ref(
  {
    title: 'Services',
    subtitle: 'Comprehensive digital solutions tailored to your business needs',
    serv:[
      {
        label:'back-end',
        name:'Laravel API Development',
        icon: '🔥',
        color: 'from-red-500 to-pink-600',
        description: 'Build robust and scalable RESTful APIs with Laravel. From authentication to complex business logic, I deliver clean, well-documented APIs that power your applications.',
        tags:['Laravel','API','Backend','Breeze','Inertia'],
        url:{
          href:'#',
          text:'Learn More',
        },
      },
      {
        label:'front-end',
        name:'Modern Frontend Development',
        icon: '⚡',
        color: 'from-yellow-400 to-orange-500',
        description: 'Create stunning, responsive user interfaces with Vue.js, Nuxt, and TailwindCSS. I focus on performance, accessibility, and seamless user experiences.',
        tags:['Vue.js','Nuxt','TailwindCSS','TypeScript'],
        url:{
          href:'#',
          text:'Learn More',
        },
      },
      {
        label:'full-stack',
        name:'Full-Stack Solutions',
        icon: '🌀',
        color: 'from-cyan-400 to-blue-500',
        description: 'End-to-end web application development using the TALL stack. From database design to polished UI, I deliver complete solutions that scale.',
        tags:['Laravel','Livewire','Alpine.js','TailwindCSS'],
        url:{
          href:'#',
          text:'Learn More',
        },
      },
      {
        label:'cloud',
        name:'Cloud & DevOps',
        icon: '☁️',
        color: 'from-purple-400 to-pink-500',
        description: 'Deploy and manage your applications on cloud platforms with CI/CD pipelines, monitoring, and optimized infrastructure for reliability and performance.',
        tags:['AWS','Docker','CI/CD','Linux'],
        url:{
          href:'#',
          text:'Learn More',
        },
      }
    ]
  }
)
</script>

<template>

  <!-- Banner Section -->
  <section class="relative min-h-[90vh] flex items-center justify-center overflow-hidden border-b border-dashed border-gray-400 dark:bg-gray-900">
    
    <!-- Gradient Background -->
    <div class="fixed inset-0 bg-gradient-to-br from-purple-600/10 via-blue-600/10 to-pink-600/10 dark:from-purple-900/20 dark:via-blue-900/20 dark:to-pink-900/20"></div>
    
    <!-- Animated Geometric Shapes -->
    <div class="fixed inset-0 overflow-hidden">
      <!-- Shape 1 -->
      <div class="fixed -top-20 -left-20 w-72 h-72 bg-purple-500/20 rounded-full blur-3xl animate-pulse"></div>
      <!-- Shape 2 -->
      <div class="fixed top-1/3 -right-20 w-96 h-96 bg-blue-500/20 rounded-full blur-3xl animate-pulse" style="animation-delay: 1s;"></div>
      <!-- Shape 3 -->
      <div class="fixed -bottom-20 left-1/3 w-80 h-80 bg-pink-500/20 rounded-full blur-3xl animate-pulse" style="animation-delay: 2s;"></div>
      
      <!-- Floating geometric elements -->
      <div class="fixed top-20 left-[10%] w-4 h-4 bg-purple-400/30 rounded-sm rotate-45 animate-bounce" style="animation-duration: 3s;"></div>
      <div class="fixed top-40 right-[15%] w-6 h-6 bg-blue-400/30 rounded-full animate-bounce" style="animation-duration: 4s;"></div>
      <div class="fixed bottom-32 left-[20%] w-3 h-3 bg-pink-400/30 rounded-sm animate-bounce" style="animation-duration: 3.5s;"></div>
      <div class="fixed bottom-20 right-[25%] w-5 h-5 bg-purple-400/30 rounded-full animate-bounce" style="animation-duration: 4.5s;"></div>
    </div>

    <!-- Grid Pattern Overlay -->
    <div class="absolute inset-0 bg-[url('data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iNjAiIGhlaWdodD0iNjAiIHZpZXdCb3g9IjAgMCA2MCA2MCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj48ZyBmaWxsPSJub25lIiBmaWxsLXJ1bGU9ImV2ZW5vZGQiPjxwYXRoIGQ9Ik0zNiAxOGMtOS45NDEgMC0xOCA4LjA1OS0xOCAxOHM4LjA1OSAxOCAxOCAxOCAxOC04LjA1OSAxOC0xOC04LjA1OS0xOC0xOC0xOHptMCAzMmMtNy43MzIgMC0xNC02LjI2OC0xNC0xNHM2LjI2OC0xNCAxNC0xNCAxNCA2LjI2OCAxNCAxNC02LjI2OCAxNC0xNCAxNHoiIGZpbGw9IiMwMDAiIGZpbGwtb3BhY2l0eT0iMC4wMyIgZmlsbC1ydWxlPSJub2tlbiIvPjwvZz48L3N2Zz4=')] opacity-30 dark:opacity-10"></div>

    <!-- Content Container -->
    <Container class="relative z-10 px-4 sm:px-6 lg:px-8 py-20">
      <div class="max-w-4xl mx-auto text-center">
        
        <!-- Badge -->
        <div class="inline-flex items-center gap-2 px-4 py-2 mb-8 text-sm font-medium text-purple-600 dark:text-purple-400 bg-purple-100 dark:bg-purple-900/30 rounded-full">
          <span class="w-2 h-2 bg-purple-500 rounded-full animate-pulse"></span>
          Available for New Projects
        </div>

        <!-- Main Title -->
        <h1 class="text-4xl sm:text-5xl md:text-6xl lg:text-7xl font-bold leading-tight mb-6">
          <span class="bg-gradient-to-r from-purple-600 via-blue-600 to-pink-600 bg-clip-text text-transparent dark:from-purple-400 dark:via-blue-400 dark:to-pink-400">
            {{ hero.title }}
          </span>
        </h1>

        <!-- Subtitle -->
        <p class="text-lg sm:text-xl text-gray-600 dark:text-gray-300 mb-10 max-w-2xl mx-auto leading-relaxed">
          {{ hero.subtitle }}
        </p>

        <!-- CTA Buttons -->
        <div class="flex flex-col sm:flex-row items-center justify-center gap-4">
          <Button variant="primary" class="w-full sm:w-auto px-8 py-4 text-base">
            {{ hero.ctaPrimary }}
          </Button>
          <Button variant="secondary" class="w-full sm:w-auto px-8 py-4 text-base">
            {{ hero.ctaSecondary }}
          </Button>
        </div>

        <!-- Trust Indicators -->
        <div class="mt-16 pt-8 border-t border-gray-200 dark:border-gray-700">
          <p class="text-sm text-gray-500 dark:text-gray-400 mb-4"> {{ hero.trust.title }} </p>
          <div class="flex flex-wrap items-center justify-center gap-8 opacity-60">
            <div v-for="indicator in hero.trust.indicator" class="text-gray-400 dark:text-gray-500 font-semibold text-sm"> {{ indicator }} </div>
            <!-- <div class="text-gray-400 dark:text-gray-500 font-semibold text-sm">Mobile Apps</div>
            <div class="text-gray-400 dark:text-gray-500 font-semibold text-sm">Cloud Solutions</div>
            <div class="text-gray-400 dark:text-gray-500 font-semibold text-sm">UI/UX Design</div> -->
          </div>
        </div>

      </div>
    </Container>

    <!-- Scroll Indicator -->
    <div class="absolute bottom-8 left-1/2 -translate-x-1/2 animate-bounce">
      <div class="w-6 h-10 border-2 border-gray-400 dark:border-gray-500 rounded-full flex justify-center pt-2">
        <div class="w-1 h-2 bg-gray-400 dark:bg-gray-500 rounded-full animate-pulse"></div>
      </div>
    </div>

  </section>


  <!-- Dev Stack Section - TALL Stack Infographic -->
  <section class="relative py-20 dark:bg-gray-900 overflow-hidden">
    <!-- Background Pattern -->
    <div class="absolute inset-0 bg-[url('data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iNjAiIGhlaWdodD0iNjAiIHZpZXdCb3g9IjAgMCA2MCA2MCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj48ZyBmaWxsPSJub25lIiBmaWxsLXJ1bGU9ImV2ZW5vZGQiPjxwYXRoIGQ9Ik0zNiAxOGMtOS45NDEgMC0xOCA4LjA1OS0xOCAxOHM4LjA1OSAxOCAxOCAxOCAxOC04LjA1OSAxOC0xOC04LjA1OS0xOC0xOC0xOHptMCAzMmMtNy43MzIgMC0xNC02LjI2OC0xNC0xNHM2LjI2OC0xNCAxNC0xNCAxNCA2LjI2OCAxNCAxNC02LjI2OCAxNC0xNCAxNHoiIGZpbGw9IiMwMDAiIGZpbGwtb3BhY2l0eT0iMC4wMyIgZmlsbC1ydWxlPSJub2tlbiIvPjwvZz48L3N2Zz4=')] opacity-30 dark:opacity-10"></div>

    <Container class="relative z-10 px-4 sm:px-6 lg:px-8">

      <!-- Section Header -->
      <div class="text-center mb-16">
        <h2 class="text-3xl sm:text-4xl md:text-5xl font-bold mb-4">
          <span class="bg-gradient-to-r from-purple-600 via-blue-600 to-pink-600 bg-clip-text text-transparent dark:from-purple-400 dark:via-blue-400 dark:to-pink-400">
            {{ stack.title }}
          </span>
        </h2>
        <p class="text-lg text-gray-600 dark:text-gray-300 max-w-2xl mx-auto">
          {{ stack.subtitle }}
        </p>
      </div>

      <!-- TALL Stack Infographic - Left to Right -->
      <div class="flex flex-col lg:flex-row items-center justify-center gap-4 lg:gap-2">
        
        <!-- TailwindCSS (T) -->
        <div class="group relative">
          <div class="absolute -inset-1 bg-gradient-to-r from-cyan-400 to-blue-500 rounded-2xl blur opacity-25 group-hover:opacity-75 transition duration-500"></div>
          <div class="relative bg-white dark:bg-gray-800 rounded-2xl p-6 sm:p-8 shadow-xl border border-gray-100 dark:border-gray-700 hover:shadow-2xl transition-all duration-300 transform hover:-translate-y-2">
            <div class="text-4xl sm:text-5xl mb-3">{{ stack.tall[0].icon }}</div>
            <h3 class="text-xl sm:text-2xl font-bold bg-gradient-to-r from-cyan-500 to-blue-600 bg-clip-text text-transparent">{{ stack.tall[0].name }}</h3>
            <p class="text-sm text-gray-500 dark:text-gray-400 mt-2">{{ stack.tall[0].description }}</p>
          </div>
        </div>

        <!-- Plus Sign -->
        <div class="hidden lg:flex items-center justify-center w-12 h-12 rounded-full bg-gradient-to-r from-purple-500 to-pink-500 text-white font-bold text-xl shadow-lg">+</div>

        <!-- Alpine.js (A) -->
        <div class="group relative">
          <div class="absolute -inset-1 bg-gradient-to-r from-orange-400 to-red-500 rounded-2xl blur opacity-25 group-hover:opacity-75 transition duration-500"></div>
          <div class="relative bg-white dark:bg-gray-800 rounded-2xl p-6 sm:p-8 shadow-xl border border-gray-100 dark:border-gray-700 hover:shadow-2xl transition-all duration-300 transform hover:-translate-y-2">
            <div class="text-4xl sm:text-5xl mb-3">{{ stack.tall[1].icon }}</div>
            <h3 class="text-xl sm:text-2xl font-bold bg-gradient-to-r from-orange-500 to-red-600 bg-clip-text text-transparent">Alpine.js</h3>
            <p class="text-sm text-gray-500 dark:text-gray-400 mt-2">{{ stack.tall[1].description }}</p>
          </div>
        </div>

        <!-- Plus Sign -->
        <div class="hidden lg:flex items-center justify-center w-12 h-12 rounded-full bg-gradient-to-r from-purple-500 to-pink-500 text-white font-bold text-xl shadow-lg">+</div>

        <!-- Livewire (L) -->
        <div class="group relative">
          <div class="absolute -inset-1 bg-gradient-to-r from-yellow-400 to-orange-500 rounded-2xl blur opacity-25 group-hover:opacity-75 transition duration-500"></div>
          <div class="relative bg-white dark:bg-gray-800 rounded-2xl p-6 sm:p-8 shadow-xl border border-gray-100 dark:border-gray-700 hover:shadow-2xl transition-all duration-300 transform hover:-translate-y-2">
            <div class="text-4xl sm:text-5xl mb-3">{{ stack.tall[2].icon }}</div>
            <h3 class="text-xl sm:text-2xl font-bold bg-gradient-to-r from-yellow-500 to-orange-600 bg-clip-text text-transparent">Livewire</h3>
            <p class="text-sm text-gray-500 dark:text-gray-400 mt-2">{{ stack.tall[2].description }}</p>
          </div>
        </div>

        <!-- Plus Sign -->
        <div class="hidden lg:flex items-center justify-center w-12 h-12 rounded-full bg-gradient-to-r from-purple-500 to-pink-500 text-white font-bold text-xl shadow-lg">+</div>

        <!-- Laravel (L) - Grouped Product Side by Side -->
        <div class="group relative">
          <div class="absolute -inset-1 bg-gradient-to-r from-red-500 to-pink-600 rounded-2xl blur opacity-25 group-hover:opacity-75 transition duration-500"></div>
          <div class="relative bg-white dark:bg-gray-800 rounded-2xl p-6 sm:p-8 shadow-xl border border-gray-100 dark:border-gray-700 hover:shadow-2xl transition-all duration-300 transform hover:-translate-y-2">
            <div class="text-4xl sm:text-5xl mb-3">{{ stack.tall[3].icon }}</div>
            <h3 class="text-xl sm:text-2xl font-bold bg-gradient-to-r from-red-500 to-pink-600 bg-clip-text text-transparent">Laravel</h3>
            <p class="text-sm text-gray-500 dark:text-gray-400 mt-2">{{ stack.tall[3].description }}</p>
            
          </div>
        </div>

      </div>

      <!-- <div class="flex gap-4 py-4 border-y border-gray-400 border-dashed my-4 ">
        <template v-for="(stack, key) in stack.tall" :key="key">
          <Cart>
            <template #header> {{ stack.name }} </template>
            <template #body> 
              <Content>{{ stack.description }}</Content>  
              <NavLink>
                {{ stack.url.text }}
              </NavLink>
            </template>
          </Cart>
        </template>
      </div> -->

      <!-- TALL Label -->
      <div class="text-center mt-12">
        <div class="inline-flex items-center gap-3 px-6 py-3 bg-gradient-to-r from-purple-600 via-blue-600 to-pink-600 rounded-full shadow-lg">
          <span class="text-white font-bold text-lg">TALL Stack</span>
          <span class="text-white/80 text-sm">|</span>
          <span class="text-white/90 text-sm">Modern Web Development</span>
        </div>
      </div>

    </Container>
  </section>


  <!-- services  -->
<Container class="relative z-10 px-4 sm:px-6 lg:px-8">

  <!-- Section Header -->
  <div class="text-center mb-16">
    <h2 class="text-3xl sm:text-4xl md:text-5xl font-bold mb-4">
      <span class="bg-gradient-to-r from-purple-600 via-blue-600 to-pink-600 bg-clip-text text-transparent dark:from-purple-400 dark:via-blue-400 dark:to-pink-400">
        {{ services.title }}
      </span>
    </h2>
    <p class="text-lg text-gray-600 dark:text-gray-300 max-w-2xl mx-auto">
      {{ services.subtitle }}
    </p>
  </div>

  <!-- Services Grid -->
  <div class="grid grid-cols-2 md:grid-cols-2 lg:grid-cols-4 gap-8">

    <div v-for="serv in services.serv" class="group relative ">
      <div class="absolute bg-white -inset-1 bg-gradient-to-r rounded-2xl blur opacity-25 group-hover:opacity-75 transition duration-500" :class="serv.color"></div>
      <div class="relative dark:bg-gray-900 rounded-2xl p-8 shadow-xl border border-gray-100 dark:border-gray-700 hover:shadow-2xl transition-all duration-300">
        <!-- Icon -->
        <div class="text-5xl mb-4">{{ serv.icon }}</div>
        
        <!-- Title -->
        <Heading>
          {{ serv.name }}
        </Heading>
        
        <!-- Description -->
        <p class="text-gray-600 dark:text-gray-300 mb-6 leading-relaxed">
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


  </div>

  <div class="grid grid-cols-4 mt-4 gap-4">
      <Cart v-for="serv in services.serv" class="">
        <div :color="serv.color" class="flex items-center justify-center h-24 "> {{ serv.label }} </div>
        <template #header>
          {{ serv.name }}
        </template>
        <template #body>
          <Content>{{serv.description}}</Content>
        </template>
      </Cart>
  </div>

</Container>

  <!-- projects  -->


  <!-- case studies  -->


  <!-- dev skills  -->


  <!-- soft skills  -->


  <!-- education  -->


  <!-- career path  -->
</template>

<style lang="postcss" scoped>
  
</style>
