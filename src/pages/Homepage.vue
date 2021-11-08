<template>
<!-- Styling Background -->
<div class="background">

       <!-- Navbar Component -->
       <Navbar />

       <!-- Container -->
       <div class="mt-5 px-8 md:pl-24 md:pr-24 md:mt-1">

       <!-- Header Section -->
       <header class="row md:flex h-auto pb-8">
              <!-- Heading -->
              <div class="w-full md:w-1/2 md:pt-10 md:pb-10 md:mb-36">
                     <h1 class="title-heading text-4xl pt-3 md:text-5xl font-extrabold md:leading-tight md:pb-3">Transfer Beda Bank Bebas Biaya Admin</h1>
                     <p class="pt-5 md:pr-16 md:leading-7 md:pt-3">Lorem ipsum dolor sit, amet consectetur adipisicing elit. Unde, facere? Lorem ipsum dolor sit amet. Lorem ipsum dolor sit, amet consectetur adipisicing.</p>
                     <!-- Button Call to Action -->
                     <button class="px-14 bg-green-800 py-2 mt-5 rounded-md mb-5 md:py-3 md:px-16 md:bg-green-800 md:rounded-md md:mt-4 hover:bg-green-900">
                            <p class="text-lg text-white font-bold">Daftar</p>
                     </button>
              </div>
              <!-- Header Images -->
              <div class="mt-14 md:headerImages md:w-1/2">
                     <img src="../assets/images/header.png" alt="headingImages">
              </div>
       </header>
       </div>

       <!-- Banner Section -->
       <div class="banner w-full">
              <img src="../assets/images/banner.png" alt="headingImages">
       </div>

       <!-- About Section -->
       <div class="about w-full bg-green-700 text-center">
              <div class="mx-auto">
              <h1 class="text-5xl pt-14 font-extrabold text-yellow-200">About Us</h1>
              <p class="text-white pt-5 w-2/3 mx-auto leading-7"><span class="font-extrabold">Rekberin</span> adalah fitur yang akan memudahkan anda untuk transaksi dengan aman dan tanpa khawatir dengan biaya admin jika mengirim uang beda bank. Tujuan kami adalah menjadi platform nomor satu di Facebook dalam transaksi jua beli dan memberikan kepercayaan.</p>
              </div>
       </div>

       <!-- Feature Section -->
       <div class="feature w-full flex">
              <div class="featureHeading w-1/2 pl-24 pb-24">
                     <h1 class="primaryFont text-5xl pt-16 font-extrabold text-green-600">Feature</h1>
                     <h3 class="text-3xl pt-10 font-bold leading-tight">Rekberin menunjang dalam bisnis anda.</h3>
                     <p class="pt-6 text-2xl pr-6 leading-tight">Kami akan membantu anda dengan berbagai fitur yang kami berikan.</p>
                     <!-- Feature Points -->
                     <div class="mt-6">
                            <div class="flex h-6 mt-2">
                                   <img src="../assets/images/checklist.png" alt="checklist">
                                   <p class="text-green-600 pl-3 font-bold">Pelayanan 24 Jam</p>
                            </div>
                            <div class="flex h-6 mt-2">
                                   <img src="../assets/images/checklist.png" alt="checklist">
                                   <p class="text-green-600 pl-3 font-bold">Laporan Secara Real-Time</p>
                            </div>
                            <div class="flex h-6 mt-2">
                                   <img src="../assets/images/checklist.png" alt="checklist">
                                   <p class="text-green-600 pl-3 font-bold">Keamanan Dalam Transaksi</p>
                            </div>
                            <div class="flex h-6 mt-2">
                                   <img src="../assets/images/checklist.png" alt="checklist">
                                   <p class="text-green-600 pl-3 font-bold">Kode Unik Berbeda</p>
                            </div>
                     </div>
              </div>
              <!-- Feature Images -->
              <div class="featureImage w-1/2 bg-green-600">
              <div class="whitespace w-1/3 bg-white"></div>
                     <img src="../assets/images/transaction.png" alt="transaction">
              </div>
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