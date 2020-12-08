<template>
    <!--
  This example requires Tailwind CSS v2.0+ 
  
  This example requires some changes to your config:
  
  ```
  // tailwind.config.js
  module.exports = {
    // ...
    plugins: [
      // ...
      require('@tailwindcss/forms'),
    ]
  }
  ```
-->
<fieldset>
  <legend class="sr-only">
    Pricing plans
  </legend>
  <ul class="relative bg-white rounded-md -space-y-px">
    <li>
      <!-- On: "bg-indigo-50 border-indigo-200 z-10", Off: "border-gray-200" -->
      <div class="relative border rounded-tl-md rounded-tr-md p-4 flex flex-col md:pl-4 md:pr-6 md:grid md:grid-cols-3">
        <label class="flex items-center text-sm cursor-pointer">
          <input name="pricing_plan" type="radio" class="focus:ring-indigo-500 h-4 w-4 text-indigo-600 cursor-pointer border-gray-300" aria-describedby="plan-option-pricing-0 plan-option-limit-0">
          <span class="ml-3 font-medium text-gray-900">Startup</span>
        </label>
        <p id="plan-option-pricing-0" class="ml-6 pl-1 text-sm md:ml-0 md:pl-0 md:text-center">
          <!-- On: "text-indigo-900", Off: "text-gray-900" -->
          <span class="font-medium">$29 / mo</span>
          <!-- On: "text-indigo-700", Off: "text-gray-500" -->
          <span>($290 / yr)</span>
        </p>
        <!-- On: "text-indigo-700", Off: "text-gray-500" -->
        <p id="plan-option-limit-0" class="ml-6 pl-1 text-sm md:ml-0 md:pl-0 md:text-right">Up to 5 active job postings</p>
      </div>
    </li>

    <li>
      <!-- On: "bg-indigo-50 border-indigo-200 z-10", Off: "border-gray-200" -->
      <div class="relative border border-gray-200 p-4 flex flex-col md:pl-4 md:pr-6 md:grid md:grid-cols-3">
        <label class="flex items-center text-sm cursor-pointer">
          <input name="pricing_plan" type="radio" class="focus:ring-indigo-500 h-4 w-4 text-indigo-600 cursor-pointer border-gray-300" aria-describedby="plan-option-pricing-1 plan-option-limit-1" checked>
          <span class="ml-3 font-medium text-gray-900">Business</span>
        </label>
        <p id="plan-option-pricing-1" class="ml-6 pl-1 text-sm md:ml-0 md:pl-0 md:text-center">
          <!-- On: "text-indigo-900", Off: "text-gray-900" -->
          <span class="font-medium">$99 / mo</span>
          <!-- On: "text-indigo-700", Off: "text-gray-500" -->
          <span>($990 / yr)</span>
        </p>
        <!-- On: "text-indigo-700", Off: "text-gray-500" -->
        <p id="plan-option-limit-1" class="ml-6 pl-1 text-sm md:ml-0 md:pl-0 md:text-right">Up to 25 active job postings</p>
      </div>
    </li>

    <li>
      <!-- On: "bg-indigo-50 border-indigo-200 z-10", Off: "border-gray-200" -->
      <div class="relative border border-gray-200 rounded-bl-md rounded-br-md p-4 flex flex-col md:pl-4 md:pr-6 md:grid md:grid-cols-3">
        <label class="flex items-center text-sm cursor-pointer">
          <input name="pricing_plan" type="radio" class="focus:ring-indigo-500 h-4 w-4 text-indigo-600 cursor-pointer border-gray-300" aria-describedby="plan-option-pricing-2 plan-option-limit-2">
          <span class="ml-3 font-medium text-gray-900">Enterprise</span>
        </label>
        <p id="plan-option-pricing-2" class="ml-6 pl-1 text-sm md:ml-0 md:pl-0 md:text-center">
          <!-- On: "text-indigo-900", Off: "text-gray-900" -->
          <span class="font-medium">$249 / mo</span>
          <!-- On: "text-indigo-700", Off: "text-gray-500" -->
          <span>($2490 / yr)</span>
        </p>
        <!-- On: "text-indigo-700", Off: "text-gray-500" -->
        <p id="plan-option-limit-2" class="ml-6 pl-1 text-sm md:ml-0 md:pl-0 md:text-right">Unlimited active job postings</p>
      </div>
    </li>
  </ul>
</fieldset>
</template>