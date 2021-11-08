<template>
<!-- Styling Background -->
<div class="background">
       <!-- Navbar Component -->
       <Navbar />
       <!-- Container -->
       <div class="px-8 md:pl-24 pr-24">
       <!-- Header Section -->
       <header class="row flex h-auto">
              <!-- Heading -->
              <div class="w-full md:w-1/2 pt-20 pb-10 mb-36">
                     <h1 class="text-5xl font-extrabold leading-tight pb-3">Transfer Beda Bank Bebas Biaya Admin</h1>
                     <p class="pr-16 leading-6">Lorem ipsum dolor sit, amet consectetur adipisicing elit. Unde, facere? Lorem ipsum dolor sit amet. Lorem ipsum dolor sit, amet consectetur adipisicing.</p>
                     <!-- Button Call to Action -->
                     <button class="py-3 px-16 bg-green-800 rounded-md mt-4">
                            <p class="text-lg text-white">Daftar</p>
                     </button>
              </div>
              <!-- Header Images -->
              <div class="headerImages w-1/2">
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