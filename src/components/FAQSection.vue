<template>
  <section class="section-padding gradient-bg">
    <div class="container-custom">
      <div class="max-w-4xl mx-auto">
        <!-- Header -->
        <div class="text-center mb-16 animate-on-scroll">
          <h2 class="text-3xl md:text-4xl lg:text-5xl font-bold text-gray-900 dark:text-white mb-6">
            Ainda com <span class="text-gradient">dúvidas</span>?
          </h2>
          <p class="text-xl text-gray-600 dark:text-gray-300">
            Respondemos as perguntas mais frequentes sobre o programa
          </p>
        </div>
        
        <!-- FAQ Items -->
        <div class="space-y-6">
          <!-- FAQ 1 -->
          <div class="animate-on-scroll" style="animation-delay: 0.1s;">
            <div 
              class="bg-white dark:bg-gray-800 rounded-2xl shadow-lg border border-gray-100 dark:border-gray-700 overflow-hidden cursor-pointer transition-all duration-300 hover:shadow-xl"
              @click="toggleFAQ(0)"
            >
              <div class="p-6 flex items-center justify-between">
                <h3 class="text-lg md:text-xl font-semibold text-gray-900 dark:text-white pr-4">
                  E se eu não vender nada?
                </h3>
                <div class="flex-shrink-0">
                  <svg 
                    :class="{ 'rotate-180': openFAQ === 0 }" 
                    class="w-6 h-6 text-primary-500 transition-transform duration-300" 
                    fill="none" 
                    stroke="currentColor" 
                    viewBox="0 0 24 24"
                  >
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7"></path>
                  </svg>
                </div>
              </div>
              <div 
                :class="{ 'max-h-96 pb-6': openFAQ === 0, 'max-h-0': openFAQ !== 0 }" 
                class="overflow-hidden transition-all duration-300"
              >
                <div class="px-6">
                  <p class="text-gray-600 dark:text-gray-300 leading-relaxed">
                    Você terá sua loja pronta e funcionando. A diferença é que meu interesse é o mesmo que o seu: 
                    <strong class="text-primary-600 dark:text-primary-400">fazer você vender</strong>. 
                    Por isso, além de criar a loja, eu te oriento sobre estratégias de vendas e acompanho seu progresso.
                  </p>
                </div>
              </div>
            </div>
          </div>
          
          <!-- FAQ 2 -->
          <div class="animate-on-scroll" style="animation-delay: 0.2s;">
            <div 
              class="bg-white dark:bg-gray-800 rounded-2xl shadow-lg border border-gray-100 dark:border-gray-700 overflow-hidden cursor-pointer transition-all duration-300 hover:shadow-xl"
              @click="toggleFAQ(1)"
            >
              <div class="p-6 flex items-center justify-between">
                <h3 class="text-lg md:text-xl font-semibold text-gray-900 dark:text-white pr-4">
                  Posso cancelar antes de 18 meses?
                </h3>
                <div class="flex-shrink-0">
                  <svg 
                    :class="{ 'rotate-180': openFAQ === 1 }" 
                    class="w-6 h-6 text-primary-500 transition-transform duration-300" 
                    fill="none" 
                    stroke="currentColor" 
                    viewBox="0 0 24 24"
                  >
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7"></path>
                  </svg>
                </div>
              </div>
              <div 
                :class="{ 'max-h-96 pb-6': openFAQ === 1, 'max-h-0': openFAQ !== 1 }" 
                class="overflow-hidden transition-all duration-300"
              >
                <div class="px-6">
                  <p class="text-gray-600 dark:text-gray-300 leading-relaxed">
                    Sim, mas existe uma cláusula de saída (como em qualquer parceria). 
                    Isso protege tanto você quanto eu. O contrato de 18 meses garante que tenhamos tempo suficiente 
                    para <strong class="text-primary-600 dark:text-primary-400">acelerar seu negócio de verdade</strong> 
                    e você tenha retorno do investimento.
                  </p>
                </div>
              </div>
            </div>
          </div>
          
          <!-- FAQ 3 -->
          <div class="animate-on-scroll" style="animation-delay: 0.3s;">
            <div 
              class="bg-white dark:bg-gray-800 rounded-2xl shadow-lg border border-gray-100 dark:border-gray-700 overflow-hidden cursor-pointer transition-all duration-300 hover:shadow-xl"
              @click="toggleFAQ(2)"
            >
              <div class="p-6 flex items-center justify-between">
                <h3 class="text-lg md:text-xl font-semibold text-gray-900 dark:text-white pr-4">
                  Preciso ter estoque pronto?
                </h3>
                <div class="flex-shrink-0">
                  <svg 
                    :class="{ 'rotate-180': openFAQ === 2 }" 
                    class="w-6 h-6 text-primary-500 transition-transform duration-300" 
                    fill="none" 
                    stroke="currentColor" 
                    viewBox="0 0 24 24"
                  >
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7"></path>
                  </svg>
                </div>
              </div>
              <div 
                :class="{ 'max-h-96 pb-6': openFAQ === 2, 'max-h-0': openFAQ !== 2 }" 
                class="overflow-hidden transition-all duration-300"
              >
                <div class="px-6">
                  <p class="text-gray-600 dark:text-gray-300 leading-relaxed">
                    Sim, você precisa ao menos ter insumos ou produtos para cadastrar. 
                    <strong class="text-primary-600 dark:text-primary-400">Eu cuido do resto</strong>: 
                    criação da loja, cadastro otimizado dos produtos, configuração de pagamentos, 
                    frete e toda a parte técnica.
                  </p>
                </div>
              </div>
            </div>
          </div>
          
          <!-- FAQ 4 -->
          <div class="animate-on-scroll" style="animation-delay: 0.4s;">
            <div 
              class="bg-white dark:bg-gray-800 rounded-2xl shadow-lg border border-gray-100 dark:border-gray-700 overflow-hidden cursor-pointer transition-all duration-300 hover:shadow-xl"
              @click="toggleFAQ(3)"
            >
              <div class="p-6 flex items-center justify-between">
                <h3 class="text-lg md:text-xl font-semibold text-gray-900 dark:text-white pr-4">
                  Vocês também ajudam a divulgar minha loja?
                </h3>
                <div class="flex-shrink-0">
                  <svg 
                    :class="{ 'rotate-180': openFAQ === 3 }" 
                    class="w-6 h-6 text-primary-500 transition-transform duration-300" 
                    fill="none" 
                    stroke="currentColor" 
                    viewBox="0 0 24 24"
                  >
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7"></path>
                  </svg>
                </div>
              </div>
              <div 
                :class="{ 'max-h-96 pb-6': openFAQ === 3, 'max-h-0': openFAQ !== 3 }" 
                class="overflow-hidden transition-all duration-300"
              >
                <div class="px-6">
                  <p class="text-gray-600 dark:text-gray-300 leading-relaxed">
                    Sim! Parte da gestão inclui orientar 
                    <strong class="text-primary-600 dark:text-primary-400">estratégias de venda e tráfego básico</strong>. 
                    Como eu ganho comissão sobre suas vendas, meu interesse é te ajudar a vender mais. 
                    Isso inclui dicas de marketing digital, otimização da loja e estratégias de conversão.
                  </p>
                </div>
              </div>
            </div>
          </div>
        </div>
        
        <!-- CTA after FAQ -->
        <div class="animate-on-scroll mt-16 text-center" style="animation-delay: 0.5s;">
          <div class="bg-white dark:bg-gray-800 p-8 rounded-2xl shadow-lg border border-gray-100 dark:border-gray-700">
            <h3 class="text-2xl font-bold text-gray-900 dark:text-white mb-4">
              Ainda tem dúvidas?
            </h3>
            <p class="text-gray-600 dark:text-gray-300 mb-6">
              Converse comigo diretamente no WhatsApp e tire todas as suas dúvidas sobre o programa.
            </p>
            <a 
              href="https://wa.me/5571991306327" 
              target="_blank"
              class="btn-whatsapp inline-flex"
            >
              <svg class="w-5 h-5" fill="currentColor" viewBox="0 0 24 24">
                <path d="M17.472 14.382c-.297-.149-1.758-.867-2.03-.967-.273-.099-.471-.148-.67.15-.197.297-.767.966-.94 1.164-.173.199-.347.223-.644.075-.297-.15-1.255-.463-2.39-1.475-.883-.788-1.48-1.761-1.653-2.059-.173-.297-.018-.458.13-.606.134-.133.298-.347.446-.52.149-.174.198-.298.298-.497.099-.198.05-.371-.025-.52-.075-.149-.669-1.612-.916-2.207-.242-.579-.487-.5-.669-.51-.173-.008-.371-.01-.57-.01-.198 0-.52.074-.792.372-.272.297-1.04 1.016-1.04 2.479 0 1.462 1.065 2.875 1.213 3.074.149.198 2.096 3.2 5.077 4.487.709.306 1.262.489 1.694.625.712.227 1.36.195 1.871.118.571-.085 1.758-.719 2.006-1.413.248-.694.248-1.289.173-1.413-.074-.124-.272-.198-.57-.347m-5.421 7.403h-.004a9.87 9.87 0 01-5.031-1.378l-.361-.214-3.741.982.998-3.648-.235-.374a9.86 9.86 0 01-1.51-5.26c.001-5.45 4.436-9.884 9.888-9.884 2.64 0 5.122 1.03 6.988 2.898a9.825 9.825 0 012.893 6.994c-.003 5.45-4.437 9.884-9.885 9.884m8.413-18.297A11.815 11.815 0 0012.05 0C5.495 0 .16 5.335.157 11.892c0 2.096.547 4.142 1.588 5.945L.057 24l6.305-1.654a11.882 11.882 0 005.683 1.448h.005c6.554 0 11.89-5.335 11.893-11.893A11.821 11.821 0 0020.885 3.488"/>
              </svg>
              Tirar dúvidas no WhatsApp
            </a>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script setup>
import { ref } from 'vue'

const openFAQ = ref(null)

const toggleFAQ = (index) => {
  openFAQ.value = openFAQ.value === index ? null : index
}
</script>