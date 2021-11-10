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
                     <h1 class="title-heading text-4xl pt-3 md:text-5xl font-extrabold md:leading-tight md:pb-3">Transfer Beda Bank Bebas Biaya Admin.</h1>
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
              <div class="mx-auto pt-12 pb-12 md:pt-14 md:pb-14">
              <h1 class="text-4xl font-bold text-yellow-200 md:text-5xl md:font-extrabold md:text-yellow-200">About Us</h1>
              <p class="text-white pt-3 px-4 leading-7 md:text-white md:pt-5 md:w-2/3 md:mx-auto md:leading-7"><span class="font-extrabold">Rekberin</span> adalah fitur yang akan memudahkan anda untuk transaksi dengan aman dan tanpa khawatir dengan biaya admin jika mengirim uang beda bank. Tujuan kami adalah menjadi platform nomor satu di Facebook dalam transaksi jua beli dan memberikan kepercayaan.</p>
              </div>
       </div>

       <!-- Feature Section -->
       <div class="feature w-full flex">
              <div class="featureHeading text-center w-full px-8 md:w-1/2 md:pl-24 md:pb-24">

              <!-- Heading -->
                     <h1 class="primaryFont text-5xl pt-16 font-extrabold text-green-600 md:text-left">Feature</h1>
                     <h3 class="text-2xl font-bold pt-5 text-left md:text-3xl md:pt-10 md:font-bold md:leading-snug">Rekberin menunjang dalam bisnis anda.</h3>

                     <!-- Sub Heading -->
                     <p class="pt-4 text-1xl text-left font-medium md:pt-6 md:text-2xl md:pr-6 md:leading-snug">Kami akan membantu anda dengan berbagai fitur yang kami berikan.</p>

                     <!-- Feature Points -->
                     <div class="mt-6">
                            <!-- Items -->
                            <div class="flex h-6 mt-2">
                                   <img src="../assets/images/checklist.png" alt="checklist">
                                   <p class="text-green-600 pl-3 font-bold">Pelayanan 24 Jam</p>
                            </div>
                            <!-- Items -->
                            <div class="flex h-6 mt-2">
                                   <img src="../assets/images/checklist.png" alt="checklist">
                                   <p class="text-green-600 pl-3 font-bold">Laporan Secara Real-Time</p>
                            </div>
                            <!-- Items -->
                            <div class="flex h-6 mt-2">
                                   <img src="../assets/images/checklist.png" alt="checklist">
                                   <p class="text-green-600 pl-3 font-bold">Keamanan Dalam Transaksi</p>
                            </div>
                            <!-- Items -->
                            <div class="flex h-6 mt-2">
                                   <img src="../assets/images/checklist.png" alt="checklist">
                                   <p class="text-green-600 pl-3 font-bold">Kode Unik Berbeda</p>
                            </div>
                     </div>
              </div>

              <!-- Feature Images -->
              <div class="featureImage md:w-1/2 bg-green-700">
              <div class="whitespace w-full md:w-1/3 md:bg-white"></div>
                     <img class="md:pl-8" src="../assets/images/transaction.png" alt="transaction">
              </div>
       </div>

       <!-- Benefits Section -->
       <div class="benefits w-full mt-28 pt-10 mb-24 md:w-full md:mt-20 md:mb-20">
              <h1 class="primaryFont text-4xl font-bold text-green-700 text-center">Manfaat</h1>
              <div class="benefitList mt-7  mx-3 flex md:justify-between md:w-2/3 md:mx-auto">
                     <div class="itemBenefits">
                            <img class="h-16 mx-auto" src="../assets/images/fast.png" alt="fast">
                            <p class="text-lg text-green-700 text-center pt-3">Transaksi Cepat</p>
                     </div>
                     <div class="itemBenefits">
                            <img class="h-16 mx-auto" src="../assets/images/shopping.png" alt="fast">
                            <p class="text-lg text-green-700 text-center pt-3">Mudah Berbelanja</p>
                     </div>
                     <div class="itemBenefits">
                            <img class="h-16 mx-auto" src="../assets/images/money.png" alt="fast">
                            <p class="text-lg text-green-700 text-center pt-3">Gratis Biaya Admin</p>
                     </div>
              </div>
       </div>

       <!-- How To Works -->
       <div class="work w-full mb-3">
              <h1 class="primaryFont text-4xl font-bold text-green-700 text-center md:text-5xl md:font-extrabold md:text-green-700">How to Work ?</h1>
       </div>

       <!-- First Feature -->
       <div class="sectionFeature md:flex md:w-full md:pl-24 md:pr-24">
              <div class="w-full md:w-1/2">
                     <img src="../assets/images/illustrationOne.png" alt="illustration">
              </div>
              <div class="w-full md:w-1/2 px-5">
                     <p class="text-green-600 font-bold pt-10 md:pt-28">#1 Hal yang dilakukan pertama kali</p>
                     <h3 class="text-2xl font-bold pt-3 text-left md:text-3xl md:pt-4 md:font-bold md:leading-tight">Pembeli lebih mudah memilih sesuai keinginan.</h3>
                     <!-- Sub Heading -->
                     <p class=" pt-4 text-1xl text-left font-medium md:pt-6 md:text-2xl md:pr-6 md:leading-snug">Pembeli memilih pesanan di Facebook kemudian mulai menghubungi admin.</p>
              </div>
       </div>

       <!-- Second Feature -->
       <div class="sectionFeature md:flex w-full md:pl-24 md:pr-24 md:mt-10">
              <div class="w-full md:w-1/2 px-5">
                     <p class="text-green-600 font-bold pt-16 md:pt-28">#2 Hal yang dilakukan penjual</p>
                     <h3 class="text-2xl font-bold pt-3 text-left md:text-3xl md:pt-4 md:font-bold md:leading-tight">Memasukkan detail produk yang akan dipesan.</h3>
                     <!-- Sub Heading -->
                     <p class=" pt-4 text-1xl text-left font-medium md:pt-6 md:text-2xl md:pr-6 md:leading-snug">Setelah mendapatkan kabar dari admin grup, maka penjual membuat detail pesanan pembeli.</p>
              </div>
              <div class="w-full md:w-1/2 px-10">
                     <img src="../assets/images/illustrationTwo.png" alt="illustration">
              </div>
       </div>

       <!-- Third Feature -->
       <div class="sectionFeature md:flex w-full md:pl-24 md:pr-24 md:mt-10">
              <div class="w-full md:w-1/2 px-5">
                     <img src="../assets/images/illustrationThree.png" alt="illustration">
              </div>
              <div class="w-full md:w-1/2 px-5">
                     <p class="text-green-600 font-bold pt-10 md:pt-28">#3 Pembeli melanjutkan pesanan.</p>
                     <h3 class="text-2xl font-bold pt-3 text-left md:text-3xl md:pt-4 md:font-bold md:leading-tight">Membayar pesanan menjadi lebih mudah.</h3>
                     <!-- Sub Heading -->
                     <p class=" pt-4 text-1xl text-left font-medium md:pt-6 md:text-2xl md:pr-6 md:leading-snug">Detail pesanan telah selesai dan dapat dilanjutkan ke proses pembayaran.</p>
              </div>
       </div>

       <!-- Fourth Feature -->
       <div class="sectionFeature md:flex w-full md:pl-24 md:pr-24 md:mt-10">
              <div class="w-full md:w-1/2 px-5">
                     <p class="text-green-600 font-bold pt-10 md:pt-28">#4 Paket dalam perjalanan </p>
                     <h3 class="text-2xl font-bold pt-3 text-left md:text-3xl md:pt-4 md:font-bold md:leading-tight">Penjual mengirim pesanan yang sesuai.</h3>
                     <!-- Sub Heading -->
                     <p class=" pt-4 text-1xl text-left font-medium md:pt-6 md:text-2xl md:pr-6 md:leading-snug">Pembayaran terkonfirmasi dan pesananpun dikirimkan oleh penjual.</p>
              </div>
              <div class="w-full md:w-1/2 px-5">
                     <img src="../assets/images/illustrationFour.png" alt="illustration">
              </div>
       </div>

       <!-- Fifth Feature -->
       <div class="sectionFeature md:flex w-full md:pl-24 md:pr-24 md:mt-10">
              <div class="w-full md:w-1/2 px-5">
                     <img src="../assets/images/illustrationFive.png" alt="illustration">
              </div>
              <div class="w-full md:w-1/2 px-5">
                     <p class="text-green-600 font-bold pt-1 md:pt-28">#5 Barangpun sampai.</p>
                     <h3 class="text-2xl font-bold pt-3 text-left md:text-3xl md:pt-4 md:font-bold md:leading-tight">Pembeli menerima barang dengan baik.</h3>
                     <!-- Sub Heading -->
                     <p class=" pt-4 text-1xl text-left font-medium md:pt-6 md:text-2xl md:pr-6 md:leading-snug">Setelah pembeli mengkonfirmasi menerima barang uangpun dikirimkan kepada penjual.</p>
              </div>
       </div>

       <!-- Register Section -->
              <div class="mt-20 py-16 register w-full bg-green-800">
                     <h1 class="text-4xl md:px-24 md:pt-10 text-center font-bold text-yellow-200 md:text-5xl md:font-extrabold md:text-yellow-200">Mulai Bisnis Anda Sekarang</h1>
                     <p class="pt-4 text-white text-center text-1xl md:text-2xl md:leading-7 md:pt-3">Daftar sekarang juga.</p>
                     <div class="text-center mx-auto">
                     <button class="mt-5 text-center px-14 bg-white text-green-800 py-2 md:mt-10 rounded-md md:py-3 md:px-16 md:bg-white md:rounded-md">
                            <p class="text-lg text-green-800 font-bold">Daftar</p>
                     </button>
                     </div>
              </div>

              <!-- Footer Section -->
              <div class="footer w-full h-auto">
                     <div class="footerList flex justify-between w-2/3 mx-auto pt-10">
                            <a href="">Bantuan</a>
                            <a href="">Tutorial</a>
                            <a href="">Daftar</a>
                            <a href="">Syarat dan Ketentuan</a>
                            <a href="">Kebijakan Privasi</a>
                     </div>
                     <div class="social flex justify-around w-1/5 mx-auto pt-8 pb-10">
                            <a href="">
                                   <img src="../assets/images/instagram.png" alt="instagram" class="h-10">
                            </a>
                            <a href="">
                                   <img src="../assets/images/twitter.png" alt="twitter" class="h-10">
                            </a>
                            <a href="">
                                   <img src="../assets/images/whatsapp.png" alt="whatsapp" class="h-10">
                            </a>
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