<template>
 
 <section>
 
 <!-- This example requires Tailwind CSS v2.0+ -->
<div class="relative bg-gray-50 pt-16 pb-20 px-4 sm:px-6 lg:pt-24 lg:pb-28 lg:px-8">
  <div class="absolute inset-0">
    <div class="bg-white h-1/3 sm:h-2/3"></div>
  </div>
  <div class="relative max-w-7xl mx-auto">
    <div class="text-center">
      <h2 class="text-3xl tracking-tight font-extrabold text-gray-900 sm:text-4xl">
        BLOG
      </h2>
      <p class="mt-3 mx-auto text-xl text-gray-500 sm:mt-4 px-4 text-justify lg:px-24">
        Quer se manter atualizado sobre ZMOT e Comportamento do Consumidor, através de conteúdos exclusivos e totalmente gratuítos? Não deixe de acessar nossos materiais super completos e cheios de dicas práticas de como acelerar seus negócios.
      </p>
    </div>
    <div class="mt-12 mx-auto grid gap-5 lg:grid-cols-3 lg:max-w-none px-4 lg:px-16">
      
      <!-- 1st block -->
      
      <div class="flex flex-col rounded-lg shadow-lg overflow-hidden">
        <div class="flex-shrink-0">
          <img class="h-48 w-full object-fill" src="~/assets/img/blog-home-section/zmot-blog-post-cover.png" alt="">
        </div>
        <div class="flex-1 bg-white p-6 flex flex-col justify-between">
          <div class="flex-1">
            
            <a href="#" class="block mt-2">
              <p class="text-xl font-semibold text-gray-900">
                ZMOT e o Comportamento do Consumidor
              </p>
              <p class="mt-3 text-base text-gray-500">
                ZMOT é a chave para você entender o consumidor moderno e poder fazer ações de Marketing Digital que geram resultado.
              </p>
            </a>
          </div>
        </div>
      </div>

      <!-- 2nd block -->

      <div class="flex flex-col rounded-lg shadow-lg overflow-hidden">
        <div class="flex-shrink-0">
          <img class="h-48 w-full object-cover" src="~/assets/img/blog-home-section/customer-experience-blog-post-cover.png" alt="">
        </div>
        <div class="flex-1 bg-white p-6 flex flex-col justify-between">
          <div class="flex-1">
            
            <a href="#" class="block mt-2">
              <p class="text-xl font-semibold text-gray-900">
                Customer Experience: Como mapear a Jornada de Compra
              </p>
              <p class="mt-3 text-base text-gray-500">
                Nesse artigo você vai aprender tudo sobre Customer Experience e Jornada de Compra e como ter controle e influencia sobre seu Funil de Vendas.
              </p>
            </a>
          </div>
        </div>
      </div>

      <!-- 3rd block -->

      <div class="flex flex-col rounded-lg shadow-lg overflow-hidden">
        <div class="flex-shrink-0">
          <img class="h-48 w-full object-cover" src="~/assets/img/blog-home-section/how-br-consume-media-blog-post-cover.png" alt="">
        </div>
        <div class="flex-1 bg-white p-6 flex flex-col justify-between">
          <div class="flex-1">
            
            <a href="#" class="block mt-2">
              <p class="text-xl font-semibold text-gray-900">
                Guia de Mídia: Como os brasileiros consomem mídia
              </p>
              <p class="mt-3 text-base text-gray-500">
                Nesse Guia de Mídia vamos te mostrar como o brasileiro tem consumido mídia e tendências de publicidade na TV, Internet, Rádio e outros meios.
              </p>
            </a>
          </div>
          
        </div>
      </div>
    </div>
  </div>
</div>

</section>

</template>

<script>
export default {
  name: "SectionBlogHome"
}
</script>