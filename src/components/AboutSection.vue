<template>
  <section class="section-padding bg-gradient-to-br from-slate-50 to-slate-100 dark:from-slate-900 dark:to-slate-800 dark-mode-transition">
    <div class="container-custom">
      <div class="max-w-4xl mx-auto text-center">
        <!-- Título Principal -->
        <h2 class="text-3xl md:text-4xl lg:text-5xl font-bold text-gray-900 dark:text-white mb-6 [text-wrap:balance] animate-on-scroll">
          Quem está por trás do <span class="text-gradient">RAGNAR Start</span>?
        </h2>
        
        <!-- Descrição Principal -->
        <div class="max-w-3xl mx-auto mb-12 animate-on-scroll">
          <p class="text-lg md:text-xl text-gray-600 dark:text-gray-200 leading-relaxed mb-6 [text-wrap:balance]">
            Somos a <strong class="text-gray-900 dark:text-white">Agência RAGNAR</strong>, especialistas em criação e gestão de e-commerces de alta performance. Com anos de experiência no mercado digital, já ajudamos centenas de empreendedores a transformar suas ideias em negócios lucrativos online.
          </p>
          
          <p class="text-lg text-gray-600 dark:text-gray-200 leading-relaxed [text-wrap:balance]">
            Nossa expertise vai além da criação de lojas virtuais. Dominamos estratégias de marketing digital, otimização de conversão e automação de vendas que fazem a diferença entre um e-commerce comum e um negócio que realmente escala.
          </p>
        </div>
        
        <!-- Cards de Autoridade -->
        <div class="grid md:grid-cols-3 gap-8 mb-12">
          <div class="card-hover-enhanced bg-white dark:bg-gray-800 p-6 rounded-xl shadow-lg dark-mode-transition animate-on-scroll">
            <div class="w-16 h-16 bg-gradient-to-br from-blue-500 to-purple-600 rounded-full flex items-center justify-center mx-auto mb-4 icon-zoom-in">
              <svg class="w-8 h-8 text-white" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 10V3L4 14h7v7l9-11h-7z"></path>
              </svg>
            </div>
            <h3 class="text-xl font-semibold text-gray-900 dark:text-white mb-2 [text-wrap:balance]">
              Performance Comprovada
            </h3>
            <p class="text-gray-600 dark:text-gray-200 [text-wrap:balance]">
              Mais de 500 e-commerces criados com resultados mensuráveis e ROI positivo
            </p>
          </div>
          
          <div class="card-hover-enhanced bg-white dark:bg-gray-800 p-6 rounded-xl shadow-lg dark-mode-transition animate-on-scroll">
            <div class="w-16 h-16 bg-gradient-to-br from-green-500 to-teal-600 rounded-full flex items-center justify-center mx-auto mb-4 icon-zoom-in">
              <svg class="w-8 h-8 text-white" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12l2 2 4-4m6 2a9 9 0 11-18 0 9 9 0 0118 0z"></path>
              </svg>
            </div>
            <h3 class="text-xl font-semibold text-gray-900 dark:text-white mb-2 [text-wrap:balance]">
              Metodologia Exclusiva
            </h3>
            <p class="text-gray-600 dark:text-gray-200 [text-wrap:balance]">
              Sistema próprio de criação e otimização que garante resultados desde o primeiro dia
            </p>
          </div>
          
          <div class="card-hover-enhanced bg-white dark:bg-gray-800 p-6 rounded-xl shadow-lg dark-mode-transition animate-on-scroll">
            <div class="w-16 h-16 bg-gradient-to-br from-orange-500 to-red-600 rounded-full flex items-center justify-center mx-auto mb-4 icon-zoom-in">
              <svg class="w-8 h-8 text-white" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17 20h5v-2a3 3 0 00-5.356-1.857M17 20H7m10 0v-2c0-.656-.126-1.283-.356-1.857M7 20H2v-2a3 3 0 015.356-1.857M7 20v-2c0-.656.126-1.283.356-1.857m0 0a5.002 5.002 0 019.288 0M15 7a3 3 0 11-6 0 3 3 0 016 0zm6 3a2 2 0 11-4 0 2 2 0 014 0zM7 10a2 2 0 11-4 0 2 2 0 014 0z"></path>
              </svg>
            </div>
            <h3 class="text-xl font-semibold text-gray-900 dark:text-white mb-2 [text-wrap:balance]">
              Suporte Especializado
            </h3>
            <p class="text-gray-600 dark:text-gray-200 [text-wrap:balance]">
              Acompanhamento personalizado com especialistas em e-commerce e marketing digital
            </p>
          </div>
        </div>
        
        <!-- CTA de Contato -->
        <div class="animate-on-scroll">
          <p class="text-lg text-gray-600 dark:text-gray-200 mb-6 max-w-2xl mx-auto [text-wrap:balance]">
            Pronto para transformar sua ideia em um e-commerce de sucesso? Vamos conversar sobre seu projeto.
          </p>
          
          <a 
            href="https://wa.me/5511999999999?text=Olá! Gostaria de saber mais sobre o RAGNAR Start e como vocês podem me ajudar a criar meu e-commerce." 
            class="btn-cta-enhanced [text-wrap:balance] sm:whitespace-nowrap"
            target="_blank"
            rel="noopener noreferrer"
          >
            <svg class="w-5 h-5" fill="currentColor" viewBox="0 0 24 24">
              <path d="M17.472 14.382c-.297-.149-1.758-.867-2.03-.967-.273-.099-.471-.148-.67.15-.197.297-.767.966-.94 1.164-.173.199-.347.223-.644.075-.297-.15-1.255-.463-2.39-1.475-.883-.788-1.48-1.761-1.653-2.059-.173-.297-.018-.458.13-.606.134-.133.298-.347.446-.52.149-.174.198-.298.298-.497.099-.198.05-.371-.025-.52-.075-.149-.669-1.612-.916-2.207-.242-.579-.487-.5-.669-.51-.173-.008-.371-.01-.57-.01-.198 0-.52.074-.792.372-.272.297-1.04 1.016-1.04 2.479 0 1.462 1.065 2.875 1.213 3.074.149.198 2.096 3.2 5.077 4.487.709.306 1.262.489 1.694.625.712.227 1.36.195 1.871.118.571-.085 1.758-.719 2.006-1.413.248-.694.248-1.289.173-1.413-.074-.124-.272-.198-.57-.347m-5.421 7.403h-.004a9.87 9.87 0 01-5.031-1.378l-.361-.214-3.741.982.998-3.648-.235-.374a9.86 9.86 0 01-1.51-5.26c.001-5.45 4.436-9.884 9.888-9.884 2.64 0 5.122 1.03 6.988 2.898a9.825 9.825 0 012.893 6.994c-.003 5.45-4.437 9.884-9.885 9.884m8.413-18.297A11.815 11.815 0 0012.05 0C5.495 0 .16 5.335.157 11.892c0 2.096.547 4.142 1.588 5.945L.057 24l6.305-1.654a11.882 11.882 0 005.683 1.448h.005c6.554 0 11.89-5.335 11.893-11.893A11.821 11.821 0 0020.885 3.488"/>
            </svg>
            Falar com Especialista
          </a>
        </div>
      </div>
    </div>
  </section>
</template>

<script setup>
// Componente não requer lógica adicional
</script>