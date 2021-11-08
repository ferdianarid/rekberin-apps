<template>
<!-- Styling Background -->
<div class="background">
       <!-- Navbar Component -->
       <Navbar />
       <!-- Container -->
       <div class="mt-5 px-8 md:pl-24 md:pr-24 md:mt-1">
       <!-- Header Section -->
       <header class="row md:flex h-auto">
              <!-- Heading -->
              <div class="w-full md:w-1/2 md:pt-10 md:pb-10 md:mb-36">
                     <h1 class="title-heading text-4xl pt-3 md:text-5xl font-extrabold md:leading-tight md:pb-3">Transfer Beda Bank Bebas Biaya Admin</h1>
                     <p class="pt-5 md:pr-16 md:leading-7 md:pt-3">Lorem ipsum dolor sit, amet consectetur adipisicing elit. Unde, facere? Lorem ipsum dolor sit amet. Lorem ipsum dolor sit, amet consectetur adipisicing.</p>
                     <!-- Button Call to Action -->
                     <button class="px-14 bg-green-800 py-2 mt-5 rounded-md mb-5 md:py-3 md:px-16 md:bg-green-800 md:rounded-md md:mt-4 hover:bg-green-900">
                            <p class="text-lg text-white">Daftar</p>
                     </button>
              </div>
              <!-- Header Images -->
              <div class="mt-14 md:headerImages md:w-1/2">
                     <img src="../assets/images/header.png" alt="headingImages">
              </div>
       </header>
       </div>
</div>
</template>

<script>
// import Navbar Component
import Navbar from "../components/Navbar.vue"
export default {
       components: {
              Navbar
       }
}
</script>

<style></style>