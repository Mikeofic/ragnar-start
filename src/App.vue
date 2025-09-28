<template>
  <div :class="{ 'dark': isDarkMode }" class="min-h-screen">
    <!-- Skip Link for Accessibility -->
    <a 
      href="#main-content" 
      class="sr-only focus:not-sr-only focus:absolute focus:top-4 focus:left-4 bg-primary-600 text-white px-4 py-2 rounded-lg z-50 focus:outline-none focus:ring-2 focus:ring-primary-300"
    >
      Pular para o conteúdo principal
    </a>
    
    <!-- Dark Mode Toggle -->
    <div class="fixed top-4 right-4 z-50">
      <button
        @click="toggleDarkMode"
        class="p-3 rounded-full bg-white dark:bg-gray-800 shadow-lg hover:shadow-xl transition-all duration-300 border border-gray-200 dark:border-gray-700"
        aria-label="Toggle dark mode"
      >
        <svg v-if="isDarkMode" class="w-5 h-5 text-yellow-500" fill="currentColor" viewBox="0 0 20 20">
          <path fill-rule="evenodd" d="M10 2a1 1 0 011 1v1a1 1 0 11-2 0V3a1 1 0 011-1zm4 8a4 4 0 11-8 0 4 4 0 018 0zm-.464 4.95l.707.707a1 1 0 001.414-1.414l-.707-.707a1 1 0 00-1.414 1.414zm2.12-10.607a1 1 0 010 1.414l-.706.707a1 1 0 11-1.414-1.414l.707-.707a1 1 0 011.414 0zM17 11a1 1 0 100-2h-1a1 1 0 100 2h1zm-7 4a1 1 0 011 1v1a1 1 0 11-2 0v-1a1 1 0 011-1zM5.05 6.464A1 1 0 106.465 5.05l-.708-.707a1 1 0 00-1.414 1.414l.707.707zm1.414 8.486l-.707.707a1 1 0 01-1.414-1.414l.707-.707a1 1 0 011.414 1.414zM4 11a1 1 0 100-2H3a1 1 0 000 2h1z" clip-rule="evenodd"></path>
        </svg>
        <svg v-else class="w-5 h-5 text-gray-700" fill="currentColor" viewBox="0 0 20 20">
          <path d="M17.293 13.293A8 8 0 016.707 2.707a8.001 8.001 0 1010.586 10.586z"></path>
        </svg>
      </button>
    </div>

    <!-- Main Content -->
    <div class="bg-white dark:bg-gray-900 transition-colors duration-300">
      <header>
        <HeroSection />
      </header>
      
      <main id="main-content">
         <PainSection />
        <SolutionSection />
        <ValuePropositionSection />
        <PricingSection />
        <TestimonialsSection />
        <AboutSection />
        <FAQSection />
        <FinalCTASection />
      </main>
      
      <footer>
        <FooterSection />
      </footer>
    </div>
  </div>
</template>

<script setup>
import { ref, onMounted } from 'vue'
import HeroSection from './components/HeroSection.vue'
import PainSection from './components/PainSection.vue'
import SolutionSection from './components/SolutionSection.vue'
import ValuePropositionSection from './components/ValuePropositionSection.vue'
import PricingSection from './components/PricingSection.vue'
import TestimonialsSection from './components/TestimonialsSection.vue'
import AboutSection from './components/AboutSection.vue'
import FAQSection from './components/FAQSection.vue'
import FinalCTASection from './components/FinalCTASection.vue'
import FooterSection from './components/FooterSection.vue'

const isDarkMode = ref(false)

const toggleDarkMode = () => {
  isDarkMode.value = !isDarkMode.value
  localStorage.setItem('darkMode', isDarkMode.value.toString())
}

onMounted(() => {
  // Check for saved dark mode preference or default to light mode
  const savedDarkMode = localStorage.getItem('darkMode')
  if (savedDarkMode !== null) {
    isDarkMode.value = savedDarkMode === 'true'
  } else {
    // Check system preference
    isDarkMode.value = window.matchMedia('(prefers-color-scheme: dark)').matches
  }
  
  // Initialize scroll animations with performance optimizations
  const observerOptions = {
    threshold: 0.1,
    rootMargin: '0px 0px -50px 0px'
  }
  
  const observer = new IntersectionObserver((entries) => {
    entries.forEach(entry => {
      if (entry.isIntersecting) {
        entry.target.classList.add('visible')
        // Unobserve after animation to improve performance
        observer.unobserve(entry.target)
      }
    })
  }, observerOptions)
  
  // Observe all elements with animate-on-scroll class
  // Use requestAnimationFrame for better performance
  requestAnimationFrame(() => {
    document.querySelectorAll('.animate-on-scroll').forEach(el => {
      observer.observe(el)
    })
  })
  
  // Optimize scroll performance
  let ticking = false
  const handleScroll = () => {
    if (!ticking) {
      requestAnimationFrame(() => {
        ticking = false
      })
      ticking = true
    }
  }
  
  window.addEventListener('scroll', handleScroll, { passive: true })
})
</script>