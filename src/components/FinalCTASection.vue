<template>
  <section class="section-padding bg-gradient-to-br from-primary-600 via-primary-700 to-primary-800 relative overflow-hidden">
    <!-- Background Elements with Parallax -->
    <div class="absolute inset-0 bg-black/20 parallax-element" data-parallax-speed="0.3"></div>
    <div class="absolute top-0 left-0 w-full h-full">
      <div class="absolute top-10 left-10 w-20 h-20 bg-white/10 rounded-full blur-xl parallax-element" data-parallax-speed="0.4"></div>
      <div class="absolute bottom-20 right-20 w-32 h-32 bg-white/5 rounded-full blur-2xl parallax-element" data-parallax-speed="0.2"></div>
      <div class="absolute top-1/2 left-1/4 w-16 h-16 bg-white/10 rounded-full blur-lg parallax-element" data-parallax-speed="0.5"></div>
    </div>
    
    <div class="container-custom relative z-10">
      <div class="max-w-4xl mx-auto text-center">
        <!-- Main CTA Content -->
        <div class="animate-on-scroll">
          <h2 class="text-3xl md:text-4xl lg:text-6xl font-bold text-white mb-6 leading-tight [text-wrap:balance]">
            Pronto para <span class="text-yellow-300">acelerar</span><br>
            seu negócio?
          </h2>
          <p class="text-xl md:text-2xl text-white/90 mb-8 leading-relaxed max-w-prose md:max-w-3xl mx-auto [text-wrap:balance]">
            Não perca mais tempo. Sua loja virtual pode estar funcionando 
            <strong class="text-yellow-300">em poucos dias</strong>.
          </p>
        </div>
        
        <!-- Value Props -->
        <div class="animate-on-scroll grid md:grid-cols-3 gap-6 mb-12" style="animation-delay: 0.2s;">
          <div class="bg-white/10 backdrop-blur-sm rounded-2xl p-6 border border-white/20">
            <div class="w-12 h-12 bg-yellow-300 rounded-xl flex items-center justify-center mx-auto mb-4">
              <svg class="w-6 h-6 text-primary-800" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 10V3L4 14h7v7l9-11h-7z"></path>
              </svg>
            </div>
            <h3 class="text-lg font-semibold text-white mb-2 [text-wrap:balance]">Setup Rápido</h3>
            <p class="text-white/80 text-sm [text-wrap:balance]">Sua loja pronta em poucos dias</p>
          </div>
          
          <div class="bg-white/10 backdrop-blur-sm rounded-2xl p-6 border border-white/20">
            <div class="w-12 h-12 bg-yellow-300 rounded-xl flex items-center justify-center mx-auto mb-4">
              <svg class="w-6 h-6 text-primary-800" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12l2 2 4-4m6 2a9 9 0 11-18 0 9 9 0 0118 0z"></path>
              </svg>
            </div>
            <h3 class="text-lg font-semibold text-white mb-2 [text-wrap:balance]">Sem Riscos</h3>
            <p class="text-white/80 text-sm [text-wrap:balance]">Só pago quando você vender</p>
          </div>
          
          <div class="bg-white/10 backdrop-blur-sm rounded-2xl p-6 border border-white/20">
            <div class="w-12 h-12 bg-yellow-300 rounded-xl flex items-center justify-center mx-auto mb-4">
              <svg class="w-6 h-6 text-primary-800" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17 20h5v-2a3 3 0 00-5.356-1.857M17 20H7m10 0v-2c0-.656-.126-1.283-.356-1.857M7 20H2v-2a3 3 0 015.356-1.857M7 20v-2c0-.656.126-1.283.356-1.857m0 0a5.002 5.002 0 019.288 0M15 7a3 3 0 11-6 0 3 3 0 016 0zm6 3a2 2 0 11-4 0 2 2 0 014 0zM7 10a2 2 0 11-4 0 2 2 0 014 0z"></path>
              </svg>
            </div>
            <h3 class="text-lg font-semibold text-white mb-2 [text-wrap:balance]">Suporte Total</h3>
            <p class="text-white/80 text-sm [text-wrap:balance]">18 meses de acompanhamento</p>
          </div>
        </div>
        
        <!-- Pricing Reminder -->
        <div class="animate-on-scroll bg-white/10 backdrop-blur-sm rounded-2xl p-8 mb-12 border border-white/20" style="animation-delay: 0.3s;">
          <div class="flex flex-col md:flex-row items-center justify-between gap-6">
            <div class="text-left">
              <h3 class="text-2xl font-bold text-white mb-2 [text-wrap:balance]">Investimento transparente</h3>
              <p class="text-white/90 [text-wrap:balance]">
                <span class="text-3xl font-bold text-yellow-300">R$ 300/mês</span> + 
                <span class="text-xl font-semibold text-yellow-300">7% sobre vendas</span>
              </p>
              <p class="text-white/80 text-sm mt-2 [text-wrap:balance]">Contrato de 18 meses • Sem pegadinhas</p>
            </div>
            <div class="text-center md:text-right">
              <p class="text-white/90 text-sm mb-2 [text-wrap:balance]">Valor total do projeto:</p>
              <p class="text-2xl font-bold text-yellow-300 [text-wrap:balance]">A partir de R$ 5.400</p>
              <p class="text-white/80 text-xs [text-wrap:balance]">Muito menos que contratar uma agência</p>
            </div>
          </div>
        </div>
        
        <!-- Main CTA Button -->
        <div class="animate-on-scroll" style="animation-delay: 0.4s;">
          <a 
            href="https://wa.me/5571991306327" 
            target="_blank"
            class="inline-flex items-center gap-3 bg-yellow-300 hover:bg-yellow-400 text-primary-800 font-bold text-xl px-12 py-6 rounded-2xl transition-all duration-300 transform hover:scale-105 hover:shadow-2xl group [text-wrap:balance] sm:whitespace-nowrap"
          >
            <svg class="w-8 h-8 group-hover:scale-110 transition-transform duration-300" fill="currentColor" viewBox="0 0 24 24">
              <path d="M17.472 14.382c-.297-.149-1.758-.867-2.03-.967-.273-.099-.471-.148-.67.15-.197.297-.767.966-.94 1.164-.173.199-.347.223-.644.075-.297-.15-1.255-.463-2.39-1.475-.883-.788-1.48-1.761-1.653-2.059-.173-.297-.018-.458.13-.606.134-.133.298-.347.446-.52.149-.174.198-.298.298-.497.099-.198.05-.371-.025-.52-.075-.149-.669-1.612-.916-2.207-.242-.579-.487-.5-.669-.51-.173-.008-.371-.01-.57-.01-.198 0-.52.074-.792.372-.272.297-1.04 1.016-1.04 2.479 0 1.462 1.065 2.875 1.213 3.074.149.198 2.096 3.2 5.077 4.487.709.306 1.262.489 1.694.625.712.227 1.36.195 1.871.118.571-.085 1.758-.719 2.006-1.413.248-.694.248-1.289.173-1.413-.074-.124-.272-.198-.57-.347m-5.421 7.403h-.004a9.87 9.87 0 01-5.031-1.378l-.361-.214-3.741.982.998-3.648-.235-.374a9.86 9.86 0 01-1.51-5.26c.001-5.45 4.436-9.884 9.888-9.884 2.64 0 5.122 1.03 6.988 2.898a9.825 9.825 0 012.893 6.994c-.003 5.45-4.437 9.884-9.885 9.884m8.413-18.297A11.815 11.815 0 0012.05 0C5.495 0 .16 5.335.157 11.892c0 2.096.547 4.142 1.588 5.945L.057 24l6.305-1.654a11.882 11.882 0 005.683 1.448h.005c6.554 0 11.89-5.335 11.893-11.893A11.821 11.821 0 0020.885 3.488"/>
            </svg>
            Quero acelerar meu negócio agora
            <svg class="w-6 h-6 group-hover:translate-x-1 transition-transform duration-300" fill="none" stroke="currentColor" viewBox="0 0 24 24">
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17 8l4 4m0 0l-4 4m4-4H3"></path>
            </svg>
          </a>
        </div>
        
        <!-- Urgency Message -->
        <div class="animate-on-scroll mt-8" style="animation-delay: 0.5s;">
          <p class="text-white/80 text-sm [text-wrap:balance]">
            ⚡ <strong class="text-yellow-300">Vagas limitadas</strong> para garantir qualidade do atendimento
          </p>
        </div>
        
        <!-- Trust Signals -->
        <div class="animate-on-scroll mt-12 pt-8 border-t border-white/20" style="animation-delay: 0.6s;">
          <div class="flex flex-col md:flex-row items-center justify-center gap-8 text-white/80">
            <div class="flex items-center gap-2">
              <svg class="w-5 h-5 text-yellow-300" fill="currentColor" viewBox="0 0 20 20">
                <path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd"></path>
              </svg>
              <span class="text-sm [text-wrap:balance]">100% Transparente</span>
            </div>
            <div class="flex items-center gap-2">
              <svg class="w-5 h-5 text-yellow-300" fill="currentColor" viewBox="0 0 20 20">
                <path fill-rule="evenodd" d="M2.166 4.999A11.954 11.954 0 0010 1.944 11.954 11.954 0 0017.834 5c.11.65.166 1.32.166 2.001 0 5.225-3.34 9.67-8 11.317C5.34 16.67 2 12.225 2 7c0-.682.057-1.35.166-2.001zm11.541 3.708a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd"></path>
              </svg>
              <span class="text-sm [text-wrap:balance]">Sem Pegadinhas</span>
            </div>
            <div class="flex items-center gap-2">
              <svg class="w-5 h-5 text-yellow-300" fill="currentColor" viewBox="0 0 20 20">
                <path d="M9 12l2 2 4-4m6 2a9 9 0 11-18 0 9 9 0 0118 0z"></path>
              </svg>
              <span class="text-sm [text-wrap:balance]">Resultados Garantidos</span>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script setup>
import { onMounted, onUnmounted } from 'vue'

let parallaxHandler = null

onMounted(() => {
  parallaxHandler = () => {
    const scrolled = window.pageYOffset
    const parallaxElements = document.querySelectorAll('.parallax-element')
    
    parallaxElements.forEach(element => {
      const speed = element.dataset.parallaxSpeed || 0.5
      const yPos = -(scrolled * speed)
      element.style.transform = `translateY(${yPos}px)`
    })
  }
  
  window.addEventListener('scroll', parallaxHandler)
})

onUnmounted(() => {
  if (parallaxHandler) {
    window.removeEventListener('scroll', parallaxHandler)
  }
})
</script>