<template>
<!-- Styling Background -->
<div id="container">
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
                     <p class="pt-5 md:pr-16 md:leading-7 md:pt-3 text-gray-600">Lorem ipsum dolor sit, amet consectetur adipisicing elit. Unde, facere? Lorem ipsum dolor sit amet. Lorem ipsum dolor sit, amet consectetur adipisicing.</p>
                     <!-- Button Call to Action -->
                     <button class="px-14 bg-brand py-2 mt-5 rounded-md mb-5 md:py-3 md:px-16 md:rounded-md md:mt-4 hover:bg-green-600">
                            <p class="text-lg text-white font-bold">Daftar</p>
                     </button>
              </div>
              <!-- Header Images -->
              <div class="mt-14 headerImages md:w-1/2">
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

              <!-- Sub About Us -->
              <p class="text-white pt-3 px-4 leading-7 md:text-white md:pt-5 md:w-2/3 md:mx-auto md:leading-7"><span class="font-extrabold">Rekberin</span> adalah fitur yang akan memudahkan anda untuk transaksi dengan aman dan tanpa khawatir dengan biaya admin jika mengirim uang beda bank. Tujuan kami adalah menjadi platform nomor satu di Facebook dalam transaksi jua beli dan memberikan kepercayaan.</p>
              </div>
       </div>

       <!-- Feature Section -->
       <div class="feature w-full flex md:flex-row flex-col">
              <div class="featureHeading text-center w-full px-8 md:w-1/2 md:pl-24 md:pb-24">

              <!-- Heading -->
                     <h1 class="primaryFont text-5xl pt-16 font-extrabold text-green-600 md:text-left">Feature</h1>
                     <h3 class="text-2xl font-bold pt-5 text-left md:text-3xl md:pt-10 md:font-bold md:leading-snug">Rekberin menunjang dalam bisnis anda.</h3>

                     <!-- Sub Heading -->
                     <p class="pt-4 text-1xl text-left font-normal md:pt-6 md:text-xl md:pr-6 md:leading-snug text-gray-600">Kami akan membantu anda dengan berbagai fitur yang kami berikan.</p>

                     <!-- Feature Points -->
                     <div class="mt-6 pb-16">
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
                     <div class="whitespace w-full md:w-1/3 md:bg-white">
                            <img class="md:pl-8" src="../assets/images/transaction.png" alt="transaction">
                     </div>
              </div>
       </div>

       <!-- Benefits Section -->
       <div class="benefits w-full mt-2 mb-24 md:w-full md:mt-20 md:mb-20">
              <h1 class="primaryFont text-4xl font-bold text-green-700 text-center">Manfaat</h1>
              <div class="benefitList mt-7  mx-3 flex md:justify-between md:w-2/3 md:mx-auto">
              <!-- Items -->
                     <div class="itemBenefits">
                            <img class="h-16 mx-auto" src="../assets/images/fast.png" alt="fast">
                            <p class="text-lg text-green-700 text-center pt-3">Transaksi Cepat</p>
                     </div>
                     <!-- Items -->
                     <div class="itemBenefits">
                            <img class="h-16 mx-auto" src="../assets/images/shopping.png" alt="fast">
                            <p class="text-lg text-green-700 text-center pt-3">Mudah Berbelanja</p>
                     </div>
                     <!-- Items -->
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
              
              <!-- Heading -->
              <div class="w-full md:w-1/2 px-5">
                     <p class="text-green-600 font-bold pt-10 md:pt-28">#1 Hal yang dilakukan pertama kali</p>
                     <h3 class="text-2xl font-bold pt-3 text-left md:text-3xl md:pt-4 md:font-bold md:leading-tight">Pembeli lebih mudah memilih sesuai keinginan.</h3>
                     <!-- Sub Heading -->
                     <p class=" pt-4 text-1xl text-left font-normal md:pt-6 md:text-xl md:pr-6 md:leading-snug text-gray-600">Pembeli memilih pesanan di Facebook kemudian mulai menghubungi admin.</p>
              </div>
       </div>

       <!-- Second Feature -->
       <div class="sectionFeature md:flex w-full md:pl-24 md:pr-24 md:mt-10">
              <div class="w-full md:w-1/2 px-5">
                     <!-- Heading -->
                     <p class="text-green-600 font-bold pt-16 md:pt-28">#2 Hal yang dilakukan penjual</p>
                     <h3 class="text-2xl font-bold pt-3 text-left md:text-3xl md:pt-4 md:font-bold md:leading-tight">Memasukkan detail produk yang akan dipesan.</h3>
                     <!-- Sub Heading -->
                     <p class=" pt-4 text-1xl text-left font-normal md:pt-6 md:text-xl md:pr-6 md:leading-snug text-gray-600">Setelah mendapatkan kabar dari admin grup, maka penjual membuat detail pesanan pembeli.</p>
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
              <!-- Heading -->
              <div class="w-full md:w-1/2 px-5">
                     <p class="text-green-600 font-bold pt-10 md:pt-28">#3 Pembeli melanjutkan pesanan.</p>
                     <h3 class="text-2xl font-bold pt-3 text-left md:text-3xl md:pt-4 md:font-bold md:leading-tight">Membayar pesanan menjadi lebih mudah.</h3>
                     <!-- Sub Heading -->
                     <p class=" pt-4 text-1xl text-left font-normal md:pt-6 md:text-xl md:pr-6 md:leading-snug text-gray-600">Detail pesanan telah selesai dan dapat dilanjutkan ke proses pembayaran.</p>
              </div>
       </div>

       <!-- Fourth Feature -->
       <div class="sectionFeature md:flex w-full md:pl-24 md:pr-24 md:mt-10">
              <!-- Heading -->
              <div class="w-full md:w-1/2 px-5">
                     <p class="text-green-600 font-bold pt-10 md:pt-28">#4 Paket dalam perjalanan </p>
                     <h3 class="text-2xl font-bold pt-3 text-left md:text-3xl md:pt-4 md:font-bold md:leading-tight">Penjual mengirim pesanan yang sesuai.</h3>
                     <!-- Sub Heading -->
                     <p class=" pt-4 text-1xl text-left font-normal md:pt-6 md:text-xl md:pr-6 md:leading-snug text-gray-600">Pembayaran terkonfirmasi dan pesananpun dikirimkan oleh penjual.</p>
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
              <!-- Heading -->
              <div class="w-full md:w-1/2 px-5">
                     <p class="text-green-600 font-bold pt-1 md:pt-28">#5 Barangpun sampai.</p>
                     <h3 class="text-2xl font-bold pt-3 text-left md:text-3xl md:pt-4 md:font-bold md:leading-tight">Pembeli menerima barang dengan baik.</h3>
                     <!-- Sub Heading -->
                     <p class=" pt-4 text-1xl text-left font-normal md:pt-6 md:text-xl md:pr-6 md:leading-snug text-gray-600">Setelah pembeli mengkonfirmasi menerima barang uangpun dikirimkan kepada penjual.</p>
              </div>
       </div>

       <!-- Frequently Asked Question -->
              <!-- FAQ -->
              <div id="container">
                     <div class="FAQ md:flex mt-16">
                            <div class="row md:w-1/2 md:pl-11 pl-6 md:pr-32 pr-6">
                            <h1 class="md:text-6xl text-5xl md:text-left text-center font-bold md:pb-8 pb-5">FAQ</h1>
                            <p class="md:text-3xl text-2xl font-normal pt-6">Apakah anda memiliki masalah dalam transaksi atau memiliki pertanyaan?</p>
                            </div>
                            <div class="row md:w-1/2 md:pb-32 pb-20 pt-10">
                            <!--  Panel 1  -->
                            <div class="md:w-auto md:pr-32 md:pl-0 pr-6 pl-6">
                            <input type="checkbox" name="panel" id="panel-1" class="hidden" />
                            <label for="panel-1" class="relative block text-black p-4 shadow border-b border-grey accordion">Apakah Rekberin aman?</label>
                            <div class="accordion__content overflow-hidden bg-grey-lighter">
                            <h2 class="accordion__header pt-4 pl-4"></h2>
                            <p class="accordion__body p-4" id="panel1">Rekberin merupakan platform yang aman karena sudah terdaftar sebagai lembaga seperti ini.</p>
                            </div>
                            </div>
                            <!--  Panel 2  -->
                            <div class="md:w-auto md:pr-32 md:pl-0 pr-6 pl-6">
                            <input type="checkbox" name="panel" id="panel-2" class="hidden" />
                            <label for="panel-2" class="relative block text-black p-4 shadow border-b border-grey accordion">Bagaimana saya menghubungi call center?</label>
                            <div class="accordion__content overflow-hidden bg-grey-lighter">
                            <h2 class="accordion__header pt-4 pl-4"></h2>
                            <p class="accordion__body p-4" id="panel1">Lorem ipsum dolor sit amet consectetur adipisicing elit. Asperiores saepe expedita, quaerat dicta facere eligendi illo quam dolorem optio distinctio?</p>
                            </div>
                            </div>
                            <!--  Panel 3  -->
                            <div class="md:w-auto md:pr-32 md:pl-0 pr-6 pl-6">
                            <input type="checkbox" name="panel" id="panel-3" class="hidden" />
                            <label for="panel-3" class="relative block text-black p-4 shadow border-b border-grey accordion">Apakah Rekberin memiliki aplikasi?</label>
                            <div class="accordion__content overflow-hidden bg-grey-lighter">
                            <h2 class="accordion__header pt-4 pl-4"></h2>
                            <p class="accordion__body p-4" id="panel1">Lorem ipsum dolor sit amet consectetur adipisicing elit. Asperiores saepe expedita, quaerat dicta facere eligendi illo quam dolorem optio distinctio?</p>
                            </div>
                            </div>
                            <!--  Panel 4  -->
                            <div class="md:w-auto md:pr-32 md:pl-0 pr-6 pl-6">
                            <input type="checkbox" name="panel" id="panel-4" class="hidden" />
                            <label for="panel-4" class="relative block text-black p-4 shadow border-b border-grey accordion">Dimana letak kantor Rekberin?</label>
                            <div class="accordion__content overflow-hidden bg-grey-lighter">
                            <h2 class="accordion__header pt-4 pl-4"></h2>
                            <p class="accordion__body p-4" id="panel1">Lorem ipsum dolor sit amet consectetur adipisicing elit. Asperiores saepe expedita, quaerat dicta facere eligendi illo quam dolorem optio distinctio?</p>
                            </div>
                            </div>
                            <!--  Panel 5  -->
                            <div class="md:w-auto md:pr-32 md:pl-0 pr-6 pl-6">
                            <input type="checkbox" name="panel" id="panel-5" class="hidden" />
                            <label for="panel-5" class="relative block text-black p-4 shadow border-b border-grey accordion">Bagaimana saya bisa mendaftar?</label>
                            <div class="accordion__content overflow-hidden bg-grey-lighter">
                            <h2 class="accordion__header pt-4 pl-4"></h2>
                            <p class="accordion__body p-4" id="panel1">Lorem ipsum dolor sit amet consectetur adipisicing elit. Asperiores saepe expedita, quaerat dicta facere eligendi illo quam dolorem optio distinctio?</p>
                            </div>
                            </div>
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

              
              </div>

              <!-- Footer Section -->
              <div class="footer w-full h-auto">
                     <div class="footerList flex flex-col items-center md:flex-row md:justify-between md:w-2/3 mx-auto pt-10">
                     <!-- List Menu Footer -->
                            <a href="" class="hover:text-green-700 md:pt-0">Bantuan</a>
                            <a href="" class="hover:text-green-700 mt-4 md:mt-0">Tutorial</a>
                            <a href="" class="hover:text-green-700 mt-4 md:mt-0">Daftar</a>
                            <a href="" class="hover:text-green-700 mt-4 md:mt-0">Syarat dan Ketentuan</a>
                            <a href="" class="hover:text-green-700 mt-4 md:mt-0">Kebijakan Privasi</a>
                     </div>

                     <!-- List Social Media -->
                     <div class="social flex justify-around w-1/3 md:w-1/5 mx-auto pt-8 pb-10">
                     <!-- Instagram -->
                            <a href="">
                                   <img src="../assets/images/instagram.png" alt="instagram" class="h-10">
                            </a>
                            <!-- Twitter -->
                            <a href="">
                                   <img src="../assets/images/twitter.png" alt="twitter" class="h-10">
                            </a>
                            <!-- WhatsApp -->
                            <a href="">
                                   <img src="../assets/images/whatsapp.png" alt="whatsapp" class="h-10">
                            </a>
                     </div>
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

<style>
label:after {
  content: "+";
  position: absolute;
  right: 1em;
  color: black;
}
input:checked + label:after {
  content: "-";
  line-height: 0.8em;
}
.accordion__content {
  max-height: 0em;
  transition: all 0.4s cubic-bezier(0.865, 0.14, 0.095, 0.87);
}
input[name="panel"]:checked ~ .accordion__content {
  /* Get this as close to what height you expect */
  max-height: 50em;
}
</style>
