<template>
    <!-- This example requires Tailwind CSS v2.0+ -->
<div class="flex items-center justify-between">
  <span class="flex-grow flex flex-col" id="toggleLabel">
    <span class="text-sm font-medium text-gray-900">Available to hire</span>
    <span class="text-sm leading-normal text-gray-500">Nulla amet tempus sit accumsan. Aliquet turpis sed sit lacinia.</span>
  </span>
  <!-- On: "bg-indigo-600", Off: "bg-gray-200" -->
  <button type="button" aria-pressed="false" aria-labelledby="toggleLabel" class="bg-gray-200 relative inline-flex flex-shrink-0 h-6 w-11 border-2 border-transparent rounded-full cursor-pointer transition-colors ease-in-out duration-200 focus:outline-none focus:ring-2 focus:ring-offset-2 focus:ring-indigo-500">
    <span class="sr-only">Use setting</span>
    <!-- On: "translate-x-5", Off: "translate-x-0" -->
    <span aria-hidden="true" class="translate-x-0 inline-block h-5 w-5 rounded-full bg-white shadow transform ring-0 transition ease-in-out duration-200"></span>
  </button>
</div>
</template>