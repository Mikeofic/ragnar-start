<template>
  <section class="section-padding bg-white dark:bg-gray-900">
    <div class="container-custom">
      <div class="max-w-4xl mx-auto text-center">
        <div class="animate-on-scroll">
          <h2 class="text-3xl md:text-4xl lg:text-5xl font-bold text-gray-900 dark:text-white mb-8">
            Você já pensou em ter sua própria <span class="text-gradient">loja online</span>, mas...
          </h2>
        </div>
        
        <div class="grid md:grid-cols-3 gap-8 mt-12">
          <!-- Pain Point 1 -->
          <div class="animate-on-scroll card-hover" style="animation-delay: 0.1s;">
            <div class="bg-red-50 dark:bg-red-900/20 p-8 rounded-2xl border border-red-100 dark:border-red-800">
              <div class="w-16 h-16 bg-red-100 dark:bg-red-800 rounded-full mx-auto mb-6 flex items-center justify-center">
                <svg class="w-8 h-8 text-red-600 dark:text-red-400" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 8c-1.657 0-3 .895-3 2s1.343 2 3 2 3 .895 3 2-1.343 2-3 2m0-8c1.11 0 2.08.402 2.599 1M12 8V7m0 1v8m0 0v1m0-1c-1.11 0-2.08-.402-2.599-1"></path>
                </svg>
              </div>
              <h3 class="text-xl font-bold text-gray-900 dark:text-white mb-4">
                Os preços que te pediram eram <span class="text-red-600 dark:text-red-400">altos demais</span>
              </h3>
              <p class="text-gray-600 dark:text-gray-300">
                Orçamentos de R$ 5.000, R$ 10.000 ou mais só para ter uma loja básica funcionando.
              </p>
            </div>
          </div>
          
          <!-- Pain Point 2 -->
          <div class="animate-on-scroll card-hover" style="animation-delay: 0.2s;">
            <div class="bg-orange-50 dark:bg-orange-900/20 p-8 rounded-2xl border border-orange-100 dark:border-orange-800">
              <div class="w-16 h-16 bg-orange-100 dark:bg-orange-800 rounded-full mx-auto mb-6 flex items-center justify-center">
                <svg class="w-8 h-8 text-orange-600 dark:text-orange-400" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M8.228 9c.549-1.165 2.03-2 3.772-2 2.21 0 4 1.343 4 3 0 1.4-1.278 2.575-3.006 2.907-.542.104-.994.54-.994 1.093m0 3h.01M21 12a9 9 0 11-18 0 9 9 0 0118 0z"></path>
                </svg>
              </div>
              <h3 class="text-xl font-bold text-gray-900 dark:text-white mb-4">
                Você não tinha certeza se <span class="text-orange-600 dark:text-orange-400">realmente iria vender</span>
              </h3>
              <p class="text-gray-600 dark:text-gray-300">
                E se investir tudo isso e não conseguir nem uma venda? O medo de não dar retorno paralisa.
              </p>
            </div>
          </div>
          
          <!-- Pain Point 3 -->
          <div class="animate-on-scroll card-hover" style="animation-delay: 0.3s;">
            <div class="bg-yellow-50 dark:bg-yellow-900/20 p-8 rounded-2xl border border-yellow-100 dark:border-yellow-800">
              <div class="w-16 h-16 bg-yellow-100 dark:bg-yellow-800 rounded-full mx-auto mb-6 flex items-center justify-center">
                <svg class="w-8 h-8 text-yellow-600 dark:text-yellow-400" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 9v2m0 4h.01m-6.938 4h13.856c1.54 0 2.502-1.667 1.732-3L13.732 4c-.77-1.333-2.694-1.333-3.464 0L3.34 16c-.77 1.333.192 3 1.732 3z"></path>
                </svg>
              </div>
              <h3 class="text-xl font-bold text-gray-900 dark:text-white mb-4">
                Ficou com medo de <span class="text-yellow-600 dark:text-yellow-400">investir e perder dinheiro</span>
              </h3>
              <p class="text-gray-600 dark:text-gray-300">
                Sem garantias, sem acompanhamento, você fica sozinho depois que a loja fica pronta.
              </p>
            </div>
          </div>
        </div>
        
        <!-- Key Insight -->
        <div class="animate-on-scroll mt-16" style="animation-delay: 0.4s;">
          <div class="bg-gradient-to-r from-primary-50 to-green-50 dark:from-primary-900/30 dark:to-green-900/30 p-8 rounded-2xl border border-primary-100 dark:border-primary-800">
            <div class="flex items-center justify-center mb-6">
              <div class="w-12 h-12 bg-primary-500 rounded-full flex items-center justify-center">
                <svg class="w-6 h-6 text-white" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 16h-1v-4h-1m1-4h.01M21 12a9 9 0 11-18 0 9 9 0 0118 0z"></path>
                </svg>
              </div>
            </div>
            <p class="text-xl md:text-2xl font-semibold text-gray-900 dark:text-white mb-4">
              👉 Esse é o maior motivo pelo qual <span class="text-primary-600 dark:text-primary-400">milhares de pessoas desistem</span> antes mesmo de começar.
            </p>
            <p class="text-lg text-gray-700 dark:text-gray-300">
              E é exatamente aqui que o <strong class="text-primary-600 dark:text-primary-400">RAGNAR Start</strong> entra.
            </p>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script setup>
// Component logic can be added here if needed
</script>