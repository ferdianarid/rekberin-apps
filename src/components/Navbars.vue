<template>
       <div class="navbar row container pl-28 pr-28 pt-5 flex justify-between items-center">
              <!-- Brand -->
              <div class="brand flex items-center ">
                     <img src="../assets/images/circle.png" alt="rekberin" width="48">
                     <h1 class="pl-2 font-bold">Rekberin</h1>
              </div>
              <!-- Navigation -->
              <div class="navigation flex items-center justify-arround ml-auto mr-3">
                     <li class="mr-5"><a href="#">Homepage</a></li>
                     <li><a href="#">Classroom</a></li>
              </div>
              <div class="mainButton">
                     <button class="login p-3 text-md text-green-600 rounded-md bg-transparent">Login</button>
                     <button class="register ml-3 p-3 text-md bg-green-600 rounded-md text-white hover:bg-green-800">Register</button>
              </div>
       </div>
</template>

<script>
export default {
       
}
</script>

<style>
/* navigation */
.navigation li {
       list-style: none;
}
</style>