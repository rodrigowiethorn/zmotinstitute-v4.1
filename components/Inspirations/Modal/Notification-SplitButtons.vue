<template>
    <!-- This example requires Tailwind CSS v2.0+ -->
<div class="fixed inset-0 flex items-end justify-center px-4 py-6 pointer-events-none sm:p-6 sm:items-start sm:justify-end">
  <!--
    Notification panel, show/hide based on alert state.

    Entering: "transform ease-out duration-300 transition"
      From: "translate-y-2 opacity-0 sm:translate-y-0 sm:translate-x-2"
      To: "translate-y-0 opacity-100 sm:translate-x-0"
    Leaving: "transition ease-in duration-100"
      From: "opacity-100"
      To: "opacity-0"
  -->
  <div class="max-w-md w-full bg-white shadow-lg rounded-lg pointer-events-auto flex ring-1 ring-black ring-opacity-5 divide-x divide-gray-200">
    <div class="w-0 flex-1 flex items-center p-4">
      <div class="w-full">
        <p class="text-sm font-medium text-gray-900">
          Receive notifications
        </p>
        <p class="mt-1 text-sm text-gray-500">
          Notications may include alerts, sounds, and badges.
        </p>
      </div>
    </div>
    <div class="flex">
      <div class="flex flex-col divide-y divide-gray-200">
        <div class="h-0 flex-1 flex">
          <button class="w-full border border-transparent rounded-none rounded-tr-lg px-4 py-3 flex items-center justify-center text-sm font-medium text-indigo-600 hover:text-indigo-500 focus:outline-none focus:z-10 focus:ring-2 focus:ring-indigo-500">
            Reply
          </button>
        </div>
        <div class="h-0 flex-1 flex">
          <button class="w-full border border-transparent rounded-none rounded-br-lg px-4 py-3 flex items-center justify-center text-sm font-medium text-gray-700 hover:text-gray-500 focus:outline-none focus:ring-2 focus:ring-indigo-500">
            Don't allow
          </button>
        </div>
      </div>
    </div>
  </div>
</div>
</template>