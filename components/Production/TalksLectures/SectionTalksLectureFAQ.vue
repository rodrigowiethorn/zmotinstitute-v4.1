<template>
    <!-- This example requires Tailwind CSS v2.0+ -->
<div class="bg-indigo-700 m-6 lg:m-12 rounded-3xl">
  

  <div class="max-w-7xl mx-auto py-12 px-4 sm:py-16 sm:px-6 lg:px-8">
    <div class="max-w-3xl mx-auto divide-y-2 divide-gray-200">
      <h2  class="text-3xl font-extrabold text-white sm:text-4xl text-center">
        Dúvidas Frequentes!?
      </h2>
      <dl class="mt-6 space-y-6 divide-y divide-gray-200">
        <div class="pt-6">
          <dt class="text-lg">
            <!-- Expand/collapse question button -->
            <button @click="isOpenFAQ_1 = !isOpenFAQ_1"  class="text-left w-full flex justify-between items-start text-white">
              <span class="font-medium text-white">
                Question one?
              </span>
              <span class="ml-6 h-7 flex items-center">
                <!--
                  Heroicon name: chevron-down

                  Open: "-rotate-180", Closed: "rotate-0"
                -->
                <svg class="-rotate-180 h-6 w-6 transform" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor" aria-hidden="true">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7" />
                </svg>
              </span>
            </button>
          </dt>
          <dd v-if="isOpenFAQ_1" class="mt-2 pr-12">
            <p class="text-base text-indigo-200">
              I don&#039;t know, but the flag is a big plus. Lorem ipsum dolor sit amet consectetur adipisicing elit. Quas cupiditate laboriosam fugiat.
            </p>
          </dd>
        </div>

        <div class="pt-6">
          <dt class="text-lg">
            <!-- Expand/collapse question button -->
            <button @click="isOpenFAQ_2 = !isOpenFAQ_2" class="text-left w-full flex justify-between items-start text-white">
              <span class="font-medium">
                How do you make holy water?
              </span>
              <span class="ml-6 h-7 flex items-center">
                <!--
                  Heroicon name: chevron-down

                  Open: "-rotate-180", Closed: "rotate-0"
                -->
                <svg class="-rotate-180 h-6 w-6 transform" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor" aria-hidden="true">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7" />
                </svg>
              </span>
            </button>
          </dt>
          <dd v-if="isOpenFAQ_2" class="mt-2 pr-12">
            <p class="text-base text-indigo-200">
              You boil the hell out of it. Lorem ipsum dolor sit amet consectetur adipisicing elit. Magnam aut tempora vitae odio inventore fuga aliquam nostrum quod porro. Delectus quia facere id sequi expedita natus.
            </p>
          </dd>
        </div>

        <div class="pt-6">
          <dt class="text-lg">
            <!-- Expand/collapse question button -->
            <button @click="isOpenFAQ_3 = !isOpenFAQ_3" class="text-left w-full flex justify-between items-start text-white">
              <span class="font-medium">
                What do you call someone with no body and no nose?
              </span>
              <span class="ml-6 h-7 flex items-center">
                <!--
                  Heroicon name: chevron-down

                  Open: "-rotate-180", Closed: "rotate-0"
                -->
                <svg class="-rotate-180 h-6 w-6 transform" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor" aria-hidden="true">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7" />
                </svg>
              </span>
            </button>
          </dt>
          <dd v-if="isOpenFAQ_3" class="mt-2 pr-12">
            <p class="text-base text-indigo-200">
              Nobody knows. Lorem ipsum dolor sit amet consectetur adipisicing elit. Culpa, voluptas ipsa quia excepturi, quibusdam natus exercitationem sapiente tempore labore voluptatem.
            </p>
          </dd>
        </div>

        <div class="pt-6">
          <dt class="text-lg">
            <!-- Expand/collapse question button -->
            <button @click="isOpenFAQ_4 = !isOpenFAQ_4" class="text-left w-full flex justify-between items-start text-white">
              <span class="font-medium">
                Why do you never see elephants hiding in trees?
              </span>
              <span class="ml-6 h-7 flex items-center">
                <!--
                  Heroicon name: chevron-down

                  Open: "-rotate-180", Closed: "rotate-0"
                -->
                <svg class="-rotate-180 h-6 w-6 transform" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor" aria-hidden="true">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7" />
                </svg>
              </span>
            </button>
          </dt>
          <dd v-if="isOpenFAQ_4" class="mt-2 pr-12">
            <p class="text-base text-indigo-200">
              Because they&#039;re so good at it. Lorem ipsum dolor sit amet consectetur adipisicing elit. Quas cupiditate laboriosam fugiat.
            </p>
          </dd>
        </div>

        <div class="pt-6">
          <dt class="text-lg">
            <!-- Expand/collapse question button -->
            <button @click="isOpenFAQ_5 = !isOpenFAQ_5" class="text-left w-full flex justify-between items-start text-white">
              <span class="font-medium">
                Why can&#039;t you hear a pterodactyl go to the bathroom?
              </span>
              <span class="ml-6 h-7 flex items-center">
                <!--
                  Heroicon name: chevron-down

                  Open: "-rotate-180", Closed: "rotate-0"
                -->
                <svg class="-rotate-180 h-6 w-6 transform" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor" aria-hidden="true">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7" />
                </svg>
              </span>
            </button>
          </dt>
          <dd v-if="isOpenFAQ_5" class="mt-2 pr-12">
            <p class="text-base text-indigo-200">
              Because the pee is silent. Lorem ipsum dolor sit amet, consectetur adipisicing elit. Ipsam, quas voluptatibus ex culpa ipsum, aspernatur blanditiis fugiat ullam magnam suscipit deserunt illum natus facilis atque vero consequatur! Quisquam, debitis error.
            </p>
          </dd>
        </div>
      </dl>
    </div>
  </div>
</div>
</template>

<script>
export default {
  name: "SectionTalksLectureFAQ",

    data: () => ({
      isOpenFAQ_1: false,
      isOpenFAQ_2: false,
      isOpenFAQ_3: false,
      isOpenFAQ_4: false,
      isOpenFAQ_5: false,
      
    })

}
</script>