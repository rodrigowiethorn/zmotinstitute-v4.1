<template>

<section id="NavBAr-section">
    <!-- This example requires Tailwind CSS v2.0+ -->
    <nav class="bg-orange-shinny">
    <div class="max-w-7xl mx-auto px-2 sm:px-6 lg:px-8">
        <div class="relative flex items-center justify-between h-16">
        <div class="absolute inset-y-0 left-0 flex items-center sm:hidden">
            <!-- Mobile menu button-->
            <button class="inline-flex items-center justify-center p-2 rounded-md text-gray-400 hover:text-white hover:bg-green-shinny focus:outline-none focus:ring-2 focus:ring-inset focus:ring-white" aria-expanded="false">
            <span class="sr-only">Open Menu</span>
            <!-- Icon when menu is closed. -->
            <!--
                Heroicon name: menu

                Menu open: "hidden", Menu closed: "block"
            -->
            <svg class="block h-6 w-6" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor" aria-hidden="true">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h16" />
            </svg>
            <!-- Icon when menu is open. -->
            <!--
                Heroicon name: x

                Menu open: "block", Menu closed: "hidden"
            -->
            <svg class="hidden h-6 w-6" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor" aria-hidden="true">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M6 18L18 6M6 6l12 12" />
            </svg>
            </button>
        </div>
        <div class="flex-1 flex items-center justify-center sm:items-stretch sm:justify-start">
            <div class="flex-shrink-0 flex items-center">
            <img class="block lg:hidden h-8 w-auto" src="~/assets/img/menu-header/zmot-logo.webp" alt="ZMOT Institute white logo with no background">
            <img class="hidden lg:block h-8 w-auto" src="~/assets/img/menu-header/zmot-logo.webp" alt="ZMOT Institute white logo with no background">
            </div>
            <div class="hidden flex-1 sm:block ml-3">
            <div class="flex space-x-4">
                
                <a href="#" class="px-3 py-2 rounded-md text-lg font-semibold text-gray-300 hover:text-white hover:bg-green-shinny">Home</a>
                <a href="#" class="px-3 py-2 rounded-md text-lg font-semibold text-gray-300 hover:text-white hover:bg-green-shinny">Blog</a>
                <a href="#" class="px-3 py-2 rounded-md text-lg font-semibold text-gray-300 hover:text-white hover:bg-green-shinny">Contato</a>
            </div>
            </div>
        </div>
        <div class="absolute inset-y-0 right-0 flex items-center pr-2 sm:static sm:inset-auto sm:ml-6 sm:pr-0">
            
            <!-- Profile dropdown -->
            <div class="ml-3 relative">
            <div>
                <button class="bg-orange-shinny flex text-sm rounded-full focus:outline-none focus:ring-2 focus:ring-offset-2 focus:ring-offset-gray-800 focus:ring-white" id="user-menu" aria-haspopup="true">
                <span class="sr-only">Open Language Picker</span>
                <img class="h-8 w-8 rounded-full" src="~/assets/img/menu-header/language.svg" alt="">
                </button>
            </div>
            <!--
                Language picker dropdown panel, show/hide based on dropdown state.

                Entering: "transition ease-out duration-100"
                From: "transform opacity-0 scale-95"
                To: "transform opacity-100 scale-100"
                Leaving: "transition ease-in duration-75"
                From: "transform opacity-100 scale-100"
                To: "transform opacity-0 scale-95"
            -->
            <div class="origin-top-right absolute right-0 mt-2 w-48 rounded-md shadow-lg py-1 bg-white ring-1 ring-black ring-opacity-5" role="menu" aria-orientation="vertical" aria-labelledby="user-menu">
                <a href="#" class="block px-4 py-2 text-sm text-gray-700 hover:bg-green-200" role="menuitem">English</a>
                <a href="#" class="block px-4 py-2 text-sm text-gray-700 hover:bg-green-100" role="menuitem">Português</a>
                <a href="#" class="block px-4 py-2 text-sm text-gray-700 hover:bg-green-50" role="menuitem">Español</a>
            </div>
            </div>
        </div>
        </div>
    </div>

    <!--
        Mobile menu, toggle classes based on menu state.

        Menu open: "block", Menu closed: "hidden"
    -->
    <div class="hidden sm:hidden">
        <div class="px-2 pt-2 pb-3 space-y-1">
        <a href="#" class="block px-3 py-2 rounded-md text-base font-medium text-gray-300 hover:text-white hover:bg-gray-700">Home</a>
        <a href="#" class="block px-3 py-2 rounded-md text-base font-medium text-gray-300 hover:text-white hover:bg-gray-700">Blog</a>
        <a href="#" class="block px-3 py-2 rounded-md text-base font-medium text-gray-300 hover:text-white hover:bg-gray-700">Contato</a>
        </div>
    </div>
    </nav>

</section>        
</template>

<script>
export default {
        name: "MenuHeaderC",
        

    //     let hamburger = document.getElementById('hamburgerbtn');

    // let mobileMenu = document.getElementById('mobileMenu');

    // hamburger.addEventListener('click', function(){
    //     mobileMenu.classList.toggle('active');
    // });


}
</script>