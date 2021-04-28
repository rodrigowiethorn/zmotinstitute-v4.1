<template>
  <div class="relative bg-gray-50 pt-16 pb-20 px-4 sm:px-6 lg:pt-24 lg:pb-28 lg:px-8">
    <div class="absolute inset-0">
      <div class="bg-white h-1/3 sm:h-2/3" />
    </div>
    <div class="relative max-w-7xl mx-auto">
      <div class="text-center">
        <h2 class="text-3xl tracking-tight font-extrabold text-gray-900 sm:text-4xl">
          Palestras Que Vão Encantar Sua Platéia
        </h2>
        <p class="mt-3 max-w-2xl mx-auto text-xl text-gray-500 sm:mt-4">
          Se você está organizando um evento e precisa de um tema super atual e relevante, com um storytelling envolvedor, nossas Palestras sobre ZMOT e Comportamento do Consumidor são o que você precisa.
        </p>
      </div>
      <div class="mt-12 max-w-lg mx-auto grid gap-5 lg:grid-cols-3 lg:max-w-none">
        <div v-for="lecture in lectures" :key="lecture.title" class="flex flex-col rounded-lg shadow-lg overflow-hidden">
          <div class="flex-shrink-0">
            <img class="h-48 w-full object-cover" :src="lecture.imageUrl" alt="" />
          </div>
          <div class="flex-1 bg-white p-6 flex flex-col justify-between">
            <div class="flex-1">
              <a :href="lecture.href" class="block mt-2">
                <p class="text-xl font-semibold text-gray-900">
                  {{ lecture.title }}
                </p>
                <p class="mt-3 text-base text-gray-500">
                  {{ lecture.description }}
                </p>
              </a>
            </div>
            <!-- <div class="mt-6 flex items-center">
             <p class="text-xl font-semibold text-gray-900">
                  {{ lecture.lectureTime }}
                </p>
            </div> -->
          </div>
        </div>
      </div>
    </div>
  </div>
</template>


<script>
const lectures = [
  {
    title: 'Influenciando o Comportamento do Consumidor com ZMOT',
    href: '#LecturesLeadForm',
    category: { name: 'Article', href: '#' },
    description:
      'Ter conhecimento de como as pessoas se comportam no processo de decisão é imprecindível para qualquer pessoa que trabalhe com Marketing e Vendas. Nessa palestra mostramos o que é ZMOT e como ele irá te ajudar.',
    date: 'Mar 16, 2020',
    datetime: '2020-03-16',
    imageUrl:
      '~/assets/img/lectures-section/influencing-consumer-behaviour-2-talk-zmot-institute.jpg',
    lectureTime: '45 min',
  },
  {
    title: 'ZMOT: O Santo Graal do Marketing Digital',
    href: '#LecturesLeadForm',
    category: { name: 'Video', href: '#' },
    description:
      'Já parou pra pensar que tudo o que fizemos no Marketing Digital é para influenciar pessoas? Essa palestra é ideal para ajudar a mostrar como o ZMOT deve estar presenten em todas as ações de Marketing que forem feitas.',
    date: 'Mar 10, 2020',
    datetime: '2020-03-10',
    imageUrl:
      '~/assets/img/lectures-section/zmot-digital-marketing-graal-talk-zmot-institute.jpg',
    lectureTime: '45 min',
  },
  {
    title: 'Hacks para Influenciar o Comportamento do Consumidor Brasileiro',
    href: '#LecturesLeadForm',
    category: { name: 'Case Study', href: '#' },
    description:
      'Precisando de dicas práticas e comprovadamente eficientes sobre como influenciar o comportamento do consumidor? Nessa palestra apresentamos alguns dos melhores Hacks para você usar nas suas campanhas de marketing.',
    date: 'Feb 12, 2020',
    datetime: '2020-02-12',
    imageUrl:
      '~/assets/img/lectures-section/hacks-consumer-behaviour-talk-zmot-institute.jpg',
    lectureTime: '45 min',
  },
]

export default {
  name: "SectionTalksLecturesOurTalks",

  data() {
    return {
      lectures,
    }
  },
}
</script>