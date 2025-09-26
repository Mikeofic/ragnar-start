<template>
  <section class="relative min-h-screen flex items-center gradient-bg overflow-hidden">
    <!-- Background Pattern -->
    <div class="absolute inset-0 opacity-5">
      <div class="absolute inset-0" style="background-image: radial-gradient(circle at 1px 1px, rgba(34,197,94,0.3) 1px, transparent 0); background-size: 50px 50px;"></div>
    </div>
    
    <!-- Floating Elements -->
    <div class="absolute top-20 left-10 w-20 h-20 bg-primary-200 dark:bg-primary-800 rounded-full opacity-20 animate-pulse-slow"></div>
    <div class="absolute bottom-32 right-16 w-16 h-16 bg-green-200 dark:bg-green-800 rounded-full opacity-20 animate-pulse-slow" style="animation-delay: 1s;"></div>
    <div class="absolute top-1/2 left-1/4 w-12 h-12 bg-primary-300 dark:bg-primary-700 rounded-full opacity-20 animate-pulse-slow" style="animation-delay: 2s;"></div>
    
    <div class="container-custom relative z-10">
      <div class="grid lg:grid-cols-2 gap-12 items-center">
        <!-- Content -->
        <div class="animate-on-scroll">
          <div class="mb-6">
            <span class="inline-block px-4 py-2 bg-primary-100 dark:bg-primary-900 text-primary-800 dark:text-primary-200 rounded-full text-sm font-semibold mb-4">
              🚀 Programa Oficial RAGNAR
            </span>
          </div>
          
          <h1 class="text-4xl md:text-5xl lg:text-6xl font-bold text-gray-900 dark:text-white mb-6 leading-tight">
            <span class="text-gradient">Sua loja virtual</span><br>
            pronta e acelerada —<br>
            <span class="text-primary-600 dark:text-primary-400">sem investimento alto inicial</span>
          </h1>
          
          <p class="text-xl text-gray-600 dark:text-gray-300 mb-4 leading-relaxed">
            Você sabe que precisa estar no digital. Mas talvez o que te trava hoje seja o custo inicial de ter uma loja bem feita.
          </p>
          
          <p class="text-lg text-gray-700 dark:text-gray-300 mb-8 leading-relaxed">
            O <strong class="text-primary-600 dark:text-primary-400">RAGNAR Start</strong> resolve isso: eu monto sua loja, gero tração junto com você e só ganho de verdade quando você vender.
          </p>
          
          <!-- CTA Button -->
          <div class="flex flex-col sm:flex-row gap-4">
            <a 
              href="https://wa.me/5571991306327" 
              target="_blank"
              rel="noopener noreferrer"
              class="btn-whatsapp text-lg animate-border-glow group"
              aria-label="Entrar em contato via WhatsApp para participar do programa RAGNAR Start"
            >
              <svg class="w-6 h-6 group-hover:scale-110 transition-transform" fill="currentColor" viewBox="0 0 24 24" aria-hidden="true">
                <path d="M17.472 14.382c-.297-.149-1.758-.867-2.03-.967-.273-.099-.471-.148-.67.15-.197.297-.767.966-.94 1.164-.173.199-.347.223-.644.075-.297-.15-1.255-.463-2.39-1.475-.883-.788-1.48-1.761-1.653-2.059-.173-.297-.018-.458.13-.606.134-.133.298-.347.446-.52.149-.174.198-.298.298-.497.099-.198.05-.371-.025-.52-.075-.149-.669-1.612-.916-2.207-.242-.579-.487-.5-.669-.51-.173-.008-.371-.01-.57-.01-.198 0-.52.074-.792.372-.272.297-1.04 1.016-1.04 2.479 0 1.462 1.065 2.875 1.213 3.074.149.198 2.096 3.2 5.077 4.487.709.306 1.262.489 1.694.625.712.227 1.36.195 1.871.118.571-.085 1.758-.719 2.006-1.413.248-.694.248-1.289.173-1.413-.074-.124-.272-.198-.57-.347m-5.421 7.403h-.004a9.87 9.87 0 01-5.031-1.378l-.361-.214-3.741.982.998-3.648-.235-.374a9.86 9.86 0 01-1.51-5.26c.001-5.45 4.436-9.884 9.888-9.884 2.64 0 5.122 1.03 6.988 2.898a9.825 9.825 0 012.893 6.994c-.003 5.45-4.437 9.884-9.885 9.884m8.413-18.297A11.815 11.815 0 0012.05 0C5.495 0 .16 5.335.157 11.892c0 2.096.547 4.142 1.588 5.945L.057 24l6.305-1.654a11.882 11.882 0 005.683 1.448h.005c6.554 0 11.89-5.335 11.893-11.893A11.821 11.821 0 0020.885 3.488"/>
              </svg>
              Quero participar do programa
            </a>
          </div>
          
          <!-- Trust Indicators -->
          <div class="mt-8 flex flex-col sm:flex-row items-start sm:items-center gap-4 sm:gap-6 text-sm text-gray-700 dark:text-gray-300">
            <div class="flex items-center gap-2">
              <svg class="w-5 h-5 text-green-600 dark:text-green-400" fill="currentColor" viewBox="0 0 20 20" aria-hidden="true">
                <path fill-rule="evenodd" d="M16.707 5.293a1 1 0 010 1.414l-8 8a1 1 0 01-1.414 0l-4-4a1 1 0 011.414-1.414L8 12.586l7.293-7.293a1 1 0 011.414 0z" clip-rule="evenodd"></path>
              </svg>
              <span>Sem custo inicial pesado</span>
            </div>
            <div class="flex items-center gap-2">
              <svg class="w-5 h-5 text-green-600 dark:text-green-400" fill="currentColor" viewBox="0 0 20 20" aria-hidden="true">
                <path fill-rule="evenodd" d="M16.707 5.293a1 1 0 010 1.414l-8 8a1 1 0 01-1.414 0l-4-4a1 1 0 011.414-1.414L8 12.586l7.293-7.293a1 1 0 011.414 0z" clip-rule="evenodd"></path>
              </svg>
              <span>Acompanhamento por 18 meses</span>
            </div>
          </div>
        </div>
        
        <!-- Visual Element -->
        <div class="animate-on-scroll" style="animation-delay: 0.3s;">
          <div class="relative">
            <!-- Main Card -->
            <div class="bg-white dark:bg-gray-800 rounded-2xl shadow-2xl p-8 transform rotate-3 hover:rotate-0 transition-transform duration-500">
              <div class="text-center">
                <div class="w-16 h-16 bg-gradient-to-r from-primary-500 to-green-500 rounded-full mx-auto mb-4 flex items-center justify-center">
                  <svg class="w-8 h-8 text-white" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 10V3L4 14h7v7l9-11h-7z"></path>
                  </svg>
                </div>
                <h3 class="text-xl font-bold text-gray-900 dark:text-white mb-2">Loja Profissional</h3>
                <p class="text-gray-600 dark:text-gray-300 text-sm">Pronta para vender desde o primeiro dia</p>
              </div>
            </div>
            
            <!-- Floating Cards -->
            <div class="absolute -top-4 -right-4 bg-primary-500 text-white p-4 rounded-lg shadow-lg transform -rotate-12 animate-pulse-slow">
              <div class="text-xs font-semibold">R$ 300/mês</div>
              <div class="text-xs opacity-80">+ 7% comissão</div>
            </div>
            
            <div class="absolute -bottom-4 -left-4 bg-green-500 text-white p-4 rounded-lg shadow-lg transform rotate-12 animate-pulse-slow" style="animation-delay: 1s;">
              <div class="text-xs font-semibold">18 meses</div>
              <div class="text-xs opacity-80">de suporte</div>
            </div>
          </div>
        </div>
      </div>
    </div>
    
    <!-- Scroll Indicator -->
    <div class="absolute bottom-8 left-1/2 transform -translate-x-1/2 animate-bounce">
      <svg class="w-6 h-6 text-gray-400" fill="none" stroke="currentColor" viewBox="0 0 24 24">
        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 14l-7 7m0 0l-7-7m7 7V3"></path>
      </svg>
    </div>
  </section>
</template>

<script setup>
// Component logic can be added here if needed
</script>