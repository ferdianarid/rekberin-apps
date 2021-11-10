<template>
       <div>
              <div class="font-sans antialiased" id="app">
                     <!-- Class Navbar -->
                     <nav class="navbar flex items-center justify-between flex-wrap pl-6 pr-6 bg-transparent p-6 md:pl-24 md:pr-24">
                            <!-- Brand and Logos -->
                            <div class="flex items-center flex-no-shrink mr-6">
                                   <!-- <svg class="fill-current h-8 w-8 mr-2" width="54" height="54" viewBox="0 0 54 54" xmlns="http://www.w3.org/2000/svg"><path d="M13.5 22.1c1.8-7.2 6.3-10.8 13.5-10.8 10.8 0 12.15 8.1 17.55 9.45 3.6.9 6.75-.45 9.45-4.05-1.8 7.2-6.3 10.8-13.5 10.8-10.8 0-12.15-8.1-17.55-9.45-3.6-.9-6.75.45-9.45 4.05zM0 38.3c1.8-7.2 6.3-10.8 13.5-10.8 10.8 0 12.15 8.1 17.55 9.45 3.6.9 6.75-.45 9.45-4.05-1.8 7.2-6.3 10.8-13.5 10.8-10.8 0-12.15-8.1-17.55-9.45-3.6-.9-6.75.45-9.45 4.05z"/></svg>
                                   <span class="font-semibold text-xl tracking-tight">Tailwind CSS</span> -->
                                   <img src="../assets/images/circle.png" alt="brandlogo" width="48">
                                   <h1 class="font-extrabold pl-3 brand-font">Rekberin</h1>
                            </div>
                     <!-- Hamburger Component -->
                     <div class="block sm:hidden">
                            <button @click="toggle" class="flex items-center px-3 py-2 border rounded text-teal-lighter border-teal-light hover:text-white hover:border-white">
                            <svg class="fill-current h-3 w-3" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg"><title>Menu</title><path d="M0 3h20v2H0V3zm0 6h20v2H0V9zm0 6h20v2H0v-2z"/></svg>
                            </button>
                     </div>
                     <!-- Hamburger Action -->
                     <div :class="open ? 'block': 'hidden'" class="w-full flex-grow sm:flex sm:items-center sm:w-auto">
                            <!-- Navigation  Links-->
                            <div class="text-sm sm:flex-grow sm:text-right">
                                   <a href="#responsive-header" class=" no-underline block mt-4 sm:mx-6 sm:inline-block sm:mt-0 text-teal-lighter hover:text-green-800 mr-4">
                                   Bantuan
                                   </a>
                                   <a href="#responsive-header" class="no-underline block mt-4 sm:mx-6 sm:inline-block sm:mt-0 text-teal-lighter hover:text-green-800 mr-4">
                                   Tutorial
                                   </a>
                                   <a href="#responsive-header" class="no-underline block mt-4 sm:mx-6 sm:inline-block sm:mt-0 text-teal-lighter hover:text-green-800 mr-4">
                                   Login
                                   </a>
                            </div>
                            <div>
                            <!-- Download Button -->
                            <a href="#" class="no-underline inline-block text-sm px-4 py-2 leading-none bg-brand border rounded text-white  hover:border-transparent hover:bg-green-600 hover:text-white mt-4 sm:mt-0">Daftar</a>
                            </div>
                     </div>
                     </nav>
              </div>       
       </div>
</template>

<script>
export default {
       data() {
              return {
                     open: false,
              }
       },
       methods: {
              toggle() {
                     this.open = !this.open
              }
       }
}
</script>

<style>
.brand-font {
       font-family: "SF Pro Display", sans-serif;
}
</style>