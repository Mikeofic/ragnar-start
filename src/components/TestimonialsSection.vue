<template>
  <section class="section-padding bg-white dark:bg-gray-900">
    <div class="container-custom">
      <div class="max-w-6xl mx-auto">
        <!-- Header -->
        <div class="text-center mb-16 animate-on-scroll">
          <h2 class="text-3xl md:text-4xl lg:text-5xl font-bold text-gray-900 dark:text-white mb-6">
            Quem já confia no <span class="text-gradient">meu trabalho</span>?
          </h2>
          <p class="text-xl text-gray-600 dark:text-gray-300">
            Referências do mercado que já escolheram a RAGNAR
          </p>
        </div>
        
        <!-- Main Testimonial -->
        <div class="animate-on-scroll mb-16" style="animation-delay: 0.2s;">
          <div class="bg-gradient-to-br from-primary-50 to-green-50 dark:from-primary-900/30 dark:to-green-900/30 p-8 md:p-12 rounded-3xl border border-primary-100 dark:border-primary-800 relative overflow-hidden">
            <!-- Background Pattern -->
            <div class="absolute top-0 right-0 w-40 h-40 bg-primary-100/50 dark:bg-primary-800/30 rounded-full -mr-20 -mt-20"></div>
            <div class="absolute bottom-0 left-0 w-32 h-32 bg-green-100/50 dark:bg-green-800/30 rounded-full -ml-16 -mb-16"></div>
            
            <div class="relative">
              <!-- Quote Icon -->
              <div class="flex justify-center mb-8">
                <div class="w-16 h-16 bg-gradient-to-r from-primary-500 to-green-500 rounded-full flex items-center justify-center">
                  <svg class="w-8 h-8 text-white" fill="currentColor" viewBox="0 0 24 24">
                    <path d="M14.017 21v-7.391c0-5.704 3.731-9.57 8.983-10.609l.995 2.151c-2.432.917-3.995 3.638-3.995 5.849h4v10h-9.983zm-14.017 0v-7.391c0-5.704 3.748-9.57 9-10.609l.996 2.151c-2.433.917-3.996 3.638-3.996 5.849h4v10h-10z"/>
                  </svg>
                </div>
              </div>
              
              <!-- Testimonial Content -->
              <blockquote class="text-center">
                <p class="text-xl md:text-2xl text-gray-700 dark:text-gray-300 mb-8 leading-relaxed italic">
                  "Ter o suporte da RAGNAR fez toda a diferença. Para quem está começando, 
                  é a melhor forma de entrar no digital sem se perder ou gastar fortunas."
                </p>
                
                <!-- Author -->
                <div class="flex items-center justify-center gap-4">
                  <div class="w-16 h-16 bg-gradient-to-r from-primary-400 to-green-400 rounded-full flex items-center justify-center">
                    <span class="text-white font-bold text-xl">PF</span>
                  </div>
                  <div class="text-left">
                    <div class="font-bold text-gray-900 dark:text-white text-lg">
                      Poli Freire
                    </div>
                    <div class="text-primary-600 dark:text-primary-400 font-semibold">
                      Referência em Personalização
                    </div>
                    <div class="text-gray-500 dark:text-gray-400 text-sm">
                      Mercado de E-commerce
                    </div>
                  </div>
                </div>
              </blockquote>
              
              <!-- Trust Badges -->
              <div class="flex justify-center mt-8">
                <div class="flex items-center gap-2 bg-white dark:bg-gray-800 px-4 py-2 rounded-full shadow-lg">
                  <svg class="w-5 h-5 text-yellow-500" fill="currentColor" viewBox="0 0 20 20">
                    <path d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.07 3.292a1 1 0 00.95.69h3.462c.969 0 1.371 1.24.588 1.81l-2.8 2.034a1 1 0 00-.364 1.118l1.07 3.292c.3.921-.755 1.688-1.54 1.118l-2.8-2.034a1 1 0 00-1.175 0l-2.8 2.034c-.784.57-1.838-.197-1.539-1.118l1.07-3.292a1 1 0 00-.364-1.118L2.98 8.72c-.783-.57-.38-1.81.588-1.81h3.461a1 1 0 00.951-.69l1.07-3.292z"></path>
                  </svg>
                  <span class="text-sm font-semibold text-gray-700 dark:text-gray-300">Autoridade do Mercado</span>
                </div>
              </div>
            </div>
          </div>
        </div>
        
        <!-- Future Testimonials Placeholder -->
        <div class="animate-on-scroll" style="animation-delay: 0.4s;">
          <div class="grid md:grid-cols-3 gap-8">
            <!-- Placeholder 1 -->
            <div class="bg-white dark:bg-gray-800 p-6 rounded-2xl shadow-lg border border-gray-100 dark:border-gray-700 text-center">
              <div class="w-12 h-12 bg-gray-200 dark:bg-gray-700 rounded-full mx-auto mb-4 flex items-center justify-center">
                <svg class="w-6 h-6 text-gray-400" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M16 7a4 4 0 11-8 0 4 4 0 018 0zM12 14a7 7 0 00-7 7h14a7 7 0 00-7-7z"></path>
                </svg>
              </div>
              <p class="text-gray-500 dark:text-gray-400 text-sm mb-4 italic">
                "Em breve, seu depoimento aqui..."
              </p>
              <div class="text-gray-400 dark:text-gray-500 text-sm">
                Próximo cliente RAGNAR START
              </div>
            </div>
            
            <!-- Placeholder 2 -->
            <div class="bg-white dark:bg-gray-800 p-6 rounded-2xl shadow-lg border border-gray-100 dark:border-gray-700 text-center">
              <div class="w-12 h-12 bg-gray-200 dark:bg-gray-700 rounded-full mx-auto mb-4 flex items-center justify-center">
                <svg class="w-6 h-6 text-gray-400" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M16 7a4 4 0 11-8 0 4 4 0 018 0zM12 14a7 7 0 00-7 7h14a7 7 0 00-7-7z"></path>
                </svg>
              </div>
              <p class="text-gray-500 dark:text-gray-400 text-sm mb-4 italic">
                "Seu sucesso será o próximo..."
              </p>
              <div class="text-gray-400 dark:text-gray-500 text-sm">
                Futuro empreendedor digital
              </div>
            </div>
            
            <!-- Placeholder 3 -->
            <div class="bg-white dark:bg-gray-800 p-6 rounded-2xl shadow-lg border border-gray-100 dark:border-gray-700 text-center">
              <div class="w-12 h-12 bg-gray-200 dark:bg-gray-700 rounded-full mx-auto mb-4 flex items-center justify-center">
                <svg class="w-6 h-6 text-gray-400" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M16 7a4 4 0 11-8 0 4 4 0 018 0zM12 14a7 7 0 00-7 7h14a7 7 0 00-7-7z"></path>
                </svg>
              </div>
              <p class="text-gray-500 dark:text-gray-400 text-sm mb-4 italic">
                "Aguardando sua história..."
              </p>
              <div class="text-gray-400 dark:text-gray-500 text-sm">
                Próxima loja de sucesso
              </div>
            </div>
          </div>
        </div>
        
        <!-- Social Proof Stats -->
        <div class="animate-on-scroll mt-16" style="animation-delay: 0.6s;">
          <div class="bg-gradient-to-r from-primary-500 to-green-500 p-8 rounded-2xl text-white text-center">
            <h3 class="text-2xl font-bold mb-6">
              Junte-se aos empreendedores que já escolheram o RAGNAR START
            </h3>
            
            <div class="grid md:grid-cols-3 gap-8">
              <div>
                <div class="text-3xl font-bold mb-2">18</div>
                <div class="text-sm opacity-90">Meses de Acompanhamento</div>
              </div>
              <div>
                <div class="text-3xl font-bold mb-2">100%</div>
                <div class="text-sm opacity-90">Transparência no Processo</div>
              </div>
              <div>
                <div class="text-3xl font-bold mb-2">0</div>
                <div class="text-sm opacity-90">Custo Inicial Pesado</div>
              </div>
            </div>
            
            <div class="mt-8">
              <a 
                href="https://wa.me/5571991306327" 
                target="_blank"
                class="inline-flex items-center gap-3 bg-white text-primary-600 font-semibold py-4 px-8 rounded-lg transition-all duration-300 transform hover:scale-105 hover:shadow-xl"
              >
                <svg class="w-5 h-5" fill="currentColor" viewBox="0 0 24 24">
                  <path d="M17.472 14.382c-.297-.149-1.758-.867-2.03-.967-.273-.099-.471-.148-.67.15-.197.297-.767.966-.94 1.164-.173.199-.347.223-.644.075-.297-.15-1.255-.463-2.39-1.475-.883-.788-1.48-1.761-1.653-2.059-.173-.297-.018-.458.13-.606.134-.133.298-.347.446-.52.149-.174.198-.298.298-.497.099-.198.05-.371-.025-.52-.075-.149-.669-1.612-.916-2.207-.242-.579-.487-.5-.669-.51-.173-.008-.371-.01-.57-.01-.198 0-.52.074-.792.372-.272.297-1.04 1.016-1.04 2.479 0 1.462 1.065 2.875 1.213 3.074.149.198 2.096 3.2 5.077 4.487.709.306 1.262.489 1.694.625.712.227 1.36.195 1.871.118.571-.085 1.758-.719 2.006-1.413.248-.694.248-1.289.173-1.413-.074-.124-.272-.198-.57-.347m-5.421 7.403h-.004a9.87 9.87 0 01-5.031-1.378l-.361-.214-3.741.982.998-3.648-.235-.374a9.86 9.86 0 01-1.51-5.26c.001-5.45 4.436-9.884 9.888-9.884 2.64 0 5.122 1.03 6.988 2.898a9.825 9.825 0 012.893 6.994c-.003 5.45-4.437 9.884-9.885 9.884m8.413-18.297A11.815 11.815 0 0012.05 0C5.495 0 .16 5.335.157 11.892c0 2.096.547 4.142 1.588 5.945L.057 24l6.305-1.654a11.882 11.882 0 005.683 1.448h.005c6.554 0 11.89-5.335 11.893-11.893A11.821 11.821 0 0020.885 3.488"/>
                </svg>
                Quero ser o próximo
              </a>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script setup>
// Component logic can be added here if needed
</script>