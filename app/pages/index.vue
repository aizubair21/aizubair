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
    subtitle: 'Tailwind, Alpine.Js, Laravel and Livewire. A full stack development solution, built by Laravel community members',
    tall: [
      {
        name: 'TailwindCSS',
        icon: 'https://logo.svgcdn.com/devicon/tailwindcss-original.png',
        color: 'from-cyan-400 to-blue-500',
        description: 'Utility-first CSS framework',
        badge:'T',
        url: {
          href:'',
          text :'Learn More',
        }
      },
      {
        name: 'Alpine.js',
        icon: 'https://static.cdnlogo.com/logos/a/15/alpine.svg',
        color: 'from-orange-400 to-red-500',
        description: 'Lightweight JavaScript framework',
        badge:'A',
        url: {
          href:'',
          text :'Learn More',
        }
      },
      {
        name: 'Livewire',
        icon: 'https://logo.svgcdn.com/devicon/livewire-original.png',
        color: 'from-yellow-400 to-orange-500',
        description: 'Full-stack framework for Laravel',
        badge:'L',
        url: {
          href:'',
          text :'Learn More',
        }
      },
      {
        name: 'Laravel',
        icon: 'https://logo.svgcdn.com/devicon/laravel-original.png',
        color: 'from-red-500 to-pink-600',
        description: 'PHP framework for web artisans',
        badge:'L',
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
    minify: [
      {
        icon:'https://logo.svgcdn.com/devicon/html5-original.png',
        name:'html',
        desc:'',
        label:'Front-End',
        filter:['front', 'back', 'api', 'srver', 'database'],
        duration:'1s'
      }, 
      {
        icon:"https://logo.svgcdn.com/devicon/css3-original.png",
        name:'css',
        desc:'',
        label:'Front-End',
        filter:['front', 'back', 'api', 'srver', 'database'],
        duration:'1.4s'
      },
      {
        icon:"https://logo.svgcdn.com/devicon-plain/javascript-plain.png",
        name:'JavaScript',
        desc:'',
        label:'Front-End',
        filter:['front', 'back', 'api', 'srver', 'database'],
        duration:'1.8s'
      },
      {
        icon:"https://logo.svgcdn.com/devicon/tailwindcss-original.png",
        name:'TailwindCSS',
        desc:'',
        label:'Front-End',
        filter:['front', 'back', 'api', 'srver', 'database'],
        duration:'2.2s'
      },
      {
        icon:"https://logo.svgcdn.com/logos/bootstrap.png",
        name:'Bootstrap',
        desc:'',
        label:'Front-End',
        filter:['front', 'back', 'api', 'srver', 'database'],
        duration:'2.6s'
      },
      {
        icon:"https://logo.svgcdn.com/logos/php.png",
        name:'Php',
        desc:'',
        label:'Front-End',
        filter:['front', 'back', 'api', 'srver', 'database'],
        duration:'1s'
      },
      {
        icon:"https://logo.svgcdn.com/devicon/laravel-original.png",
        name:'Laravel',
        desc:'',
        label:'Front-End',
        filter:['front', 'back', 'api', 'srver', 'database'],
        duration:'1.4s'
      },
      {
        icon:"https://logo.svgcdn.com/logos/vue.png",
        name:'VueJs',
        desc:'',
        label:'Front-End',
        filter:['front', 'back', 'api', 'srver', 'database'],
        duration:'1.8s'
      },
      {
        icon:"https://logo.svgcdn.com/devicon/livewire-original.png",
        name:'Livewire',
        desc:'',
        label:'Front-End',
        filter:['front', 'back', 'api', 'srver', 'database'],
        duration:'2s'
      },
      {
        icon:"https://logo.svgcdn.com/devicon/nuxt-original.png",
        name:'NuxtJs',
        desc:'',
        label:'Front-End',
        filter:['front', 'back', 'api', 'srver', 'database'],
        duration:'1.5s'
      },
      
    ],
    serv:[
      {
        label:'back-end',
        name:'Laravel REST API',
        icon: 'https://logo.svgcdn.com/devicon/laravel-original-wordmark.png',
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
        name:'Modern Frontend',
        icon: 'https://logo.svgcdn.com/devicon/nuxt-original-wordmark.png',
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
        icon: 'https://logo.svgcdn.com/devicon/laravel-original-wordmark.png',
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
        icon: 'https://logo.svgcdn.com/devicon/cloudflare-original.png',
        color: 'from-purple-400 to-pink-500',
        description: 'Deploy and manage your applications on cloud platforms with CI/CD pipelines, monitoring, and optimized infrastructure for reliability and performance.',
        tags:['AWS','Docker','CI/CD','Linux'],
        url:{
          href:'#',
          text:'Learn More',
        },
      },
      {
        label:'cloud',
        name:'Inertia-Laravel',
        icon: 'https://logo.svgcdn.com/devicon/inertiajs-original-wordmark.png',
        color: 'from-purple-400 to-pink-500',
        description: 'Deploy and manage your applications on cloud platforms with CI/CD pipelines, monitoring, and optimized infrastructure for reliability and performance.',
        tags:['AWS','Docker','CI/CD','Linux'],
        url:{
          href:'#',
          text:'Learn More',
        },
      },
    ]
  }
)



const projects = ref({
    title:'Projects',
    subtitle:'',
    collection:[
        {
            name:'selpoint',
            filter:['laravel', 'full-stack', 'ecommerce'],
            badge:'Laravel',
            status:'Dev',
            icon:'',
            color:'',
            tags:'',
            description:'A comission based mulitvendor e-commerce starter',
            
            url:{
                href:'',
                text:'Details',
            },
        },
        {
            name:'selpoint',
            filter:['laravel', 'full-stack', 'ecommerce'],
            badge:'Laravel',
            status:'Dev',
            icon:'',
            color:'',
            tags:'',
            description:'A comission based mulitvendor e-commerce starter',
            
            url:{
                href:'',
                text:'Details',
            },
        }
   ]


});


/**
 * case studeis around php, laravel, javascript, livewire, alpine, dom, subscription, Blade layout, etc
*/
const studies = ref(
  {
    title:'Case Study',
    subtitle:'',
    collection:[
      {
        name:'',
        icon:'https://logo.svgcdn.com/simple-icons/pinboard-dark.png',
        label:'Laravel',
        badge:'',
        desc:'',
        url:{
          href:'',
          text:'Descover More',
        }
      }
    ]
  }
);
</script>

<template>

  <!-- Banner Section -->
  <section class="relative min-h-[90vh] flex items-center justify-center overflow-hidden dark:bg-gray-900">
    
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
          <div class="flex items-center justify-center gap-4 opacity-60">
            <div v-for="indicator in hero.trust.indicator" class="text-gray-400 dark:text-gray-500 font-semibold text-sm"> {{ indicator }} </div>
          </div>
        </div>

      </div>
    </Container>

    <!-- Scroll Indicator -->
    <div class="absolute bottom-2 left-1/2 -translate-x-1/2 animate-bounce">
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
      <SectionHeading :heading="stack.title" :subHeading="stack.subtitle"  />

      <!-- stacks  -->
      <div class="flex flex-wrap items-center justify-center lg:gap-8 py-4 my-4 ">
        <Cart v-for="(stack, key) in stack.tall" :key="key" class="w-[160px]">
          <NuxtLink class="group relative text-center">
            <Img :src="stack.icon"  class="mx-auto h-32 p-4 animate-pulse cursor-pointer" :style="`animation-duration: ${key+1}s`" />
            <Content class="transition-all duration-200"> {{ stack.name }} </Content>
          </NuxtLink>
          <Badges :title="stack.badge" position="top-1 left-1" color="bg-pink-900 text-white" />
        </Cart>
      </div>


      <!-- TALL Label -->
      <div class="text-center">
        <div class="inline-flex items-center gap-3 px-6 py-3 bg-gradient-to-r from-purple-600 via-blue-600 to-pink-600 rounded-full shadow-lg">
          <span class="text-white font-bold text-lg">TALL Stack</span>
          <span class="text-white/80 text-sm">|</span>
          <span class="text-white/90 text-sm">Modern Web Development</span>
        </div>
      </div>


    </Container>
  </section>


  <!-- services  -->
  <Container class="border-b border-gray-400 border-dashed relative z-10 px-4 sm:px-6 lg:px-8 py-20">

    <!-- Section Header -->
    <SectionHeading :heading="services.title" :subHeading="services.subtitle"  />

    <Grid max="300px" gap="10px">
      <Cart v-for="(serv, key) in services.serv" :key="key" class="hover:shadow-3xl lg:bg-gradient-to-r" >
        <!-- <div class="absolute -inset-1 bg-gradient-to-r rounded-2xl blur opacity-25 group-hover:opacity-75 transition duration-500" :class="serv.color"></div> -->

        <template #img>
          <Img :src="serv.icon" class="h-full w-full p-4 object-cover group-hover:shadow-3xl" />
        </template>
      
        <template #header> {{ serv.name }} </template>
        <template #body>
          <Content>{{serv.description}}</Content>
          <NavLink>{{serv.url.text}}</NavLink>
        </template>
      </Cart>
    </Grid> 

    <br>
    <div class="flex flex-wrap items-center justify-center lg:gap-8 items-center py-4 my-4 ">
          <Cart v-for="(min, key) in services.minify" :key="key" class="w-[160px] relative">
            <Badges :title="min.label" position="top-1 left-1" color="bg-indigo-500 text-white"/>
            <NuxtLink class="group relative text-center">
              <Img :src="min.icon"  class="mx-auto h-32 p-4 animate-pulse cursor-pointer" :style="`animation-duration: ${min.duration}`" />
              <Content class="group-hover:shadow-3xl"> {{ min.name.toUpperCase() }} </Content>
            </NuxtLink>
          </Cart>
        </div>

  </Container>


  <!-- projects  -->
  <Container class="border-b border-gray-400 border-dashed relative z-10 px-4 sm:px-6 lg:px-8 py-20">
    <div class="flex flex-wrap justify-center gap-10">
      <div class="rounded-full px-3 bg-white text-sm" >LIVE</div>
    </div>
    <SectionHeading :heading="projects.title" />
    <br>

    <!-- projects  -->
    <Grid min="200px" max="1fr" gap="20px">
      <Cart v-for="(proj, key) in projects.collection" :key >

        <div class="relative h-48 lg:h-36 w-auto">
          <Img src="placeholder.jpg" class="h-full w-full object-cover hover:scale-125" />

          <Badges :title='proj.badge' position="bottom-1 right-2" color="bg-indigo-600 text-white" />
          <Badges :title='proj.status' position="top-1 left-2" color="bg-gray-600 text-white" />
        </div>

        <template #header>{{ proj.name.toUpperCase() }}</template>
        <template #body>
          <Content>
            {{ proj.description }}
          </Content>
          <NavLink>
            {{ proj.url.text }}
          </NavLink>
        </template>
        <div class="absolute -inset-1 bg-gradient-to-r rounded-2xl blur opacity-25 group-hover:opacity-75 transition duration-500" :class="proj.color"></div>
      </Cart>
    </Grid>
  </Container>


  <!-- case studies  -->
  <Container>
    <SectionHeading :heading="studies.title"/>
    <br>

    <Grid min="200px" max="1fr" gap="20px">
      <Cart v-for="(cases, key) in studies.collection" :key >

        <div class="relative h-48 lg:h-36 w-auto">
          <Img :src="cases.icon" class="h-full w-full object-cover hover:scale-125" />

          <!-- <Badges :title='cases.badge' position="bottom-1 right-2" color="bg-indigo-600 text-white" /> -->
          <Badges :title='cases.label' position="top-1 left-2" color="bg-gray-600 text-white" />
        </div>

        <template #header>{{ cases.name.toUpperCase() }}</template>
        <template #body>
          <Content>
            {{ cases.description }}
          </Content>
          <NavLink>
            {{ cases.url.text }}
          </NavLink>
        </template>
      </Cart>
    </Grid>
  </Container>

  <!-- dev skills  -->


  <!-- soft skills  -->


  <!-- education  -->


  <!-- career path  -->


</template>

<style lang="postcss" scoped>
  
</style>
