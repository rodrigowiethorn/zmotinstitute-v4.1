<template>

<section id="Banner-section">
<div id="hero-section" class="bg-orange-100 m-6 lg:m-12 rounded-3xl" > <!-- bg-amber-100 -->
    <div class="container mx-auto flex px-5 py-6 lg:py-24 md:flex-row flex-col items-center">
    <div class="lg:flex-grow md:w-1/2 lg:pr-16 md:pr-8 flex flex-col md:items-start md:text-left mb-8 md:mb-0 items-center text-center">
      <h1 class="title-font text-5xl lg:text-6xl mb-4 font-semibold text-orange-shinny">Evangelizando ZMOT 
        <br class="hidden lg:inline-block">Palestras, Webinars 
         <br class="hidden lg:inline-block">& Eventos Corporativos
      </h1>
      <!-- <p class="mb-8 leading-relaxed text-red-700 font-semibold text-xl mt-4">Nossa Consultoria de Marketing te ajuda a otimizar seu Mix de Marketing com ZMOT.</p> -->
        <div class="mt-10 sm:flex sm:justify-center lg:justify-start">
          <div class="rounded-md shadow">
            <a href="#ZmotAuditFeatures" class="uppercase w-full flex items-center justify-center px-8 py-3 border border-transparent text-base font-medium rounded-md text-white bg-green-shinny md:py-4 md:text-lg md:px-10">
              Mais Informações
            </a>
          </div>
          <div class="mt-3 rounded-md shadow-md sm:mt-0 sm:ml-3 uppercase">
            <a href="#" class="w-full flex items-center justify-center px-8 py-3 border border-transparent text-base font-medium rounded-md text-indigo-600 bg-white hover:bg-indigo-600 hover:text-white md:py-4 md:text-lg md:px-10">
              Chat Online
            </a>
          </div>
        </div>
      
      <!-- <div class="flex justify-center">
        <button class="inline-flex text-white bg-indigo-500 border-0 py-2 px-6 focus:outline-none hover:bg-indigo-600 rounded text-lg">Button</button>
        <button class="ml-4 inline-flex text-gray-700 bg-gray-200 border-0 py-2 px-6 focus:outline-none hover:bg-gray-300 rounded text-lg">Button</button>
      </div> -->
    </div>
    <div v-if="$device.isDesktop"  class="lg:max-w-lg md:w-1/2 w-5/6 lg:transform lg:scale-125 lg:mr-12">
      <img class="object-cover object-center rounded" alt="hero" src="~/assets/img/services-section/service-lecture.png">
    </div>
  </div>
</div>
</section>

</template>

<script>
export default {
  name: "SectionTalksLecturesHero",

}
</script>