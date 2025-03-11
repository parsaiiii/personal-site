<template>
    <div class="testi-item bg-white carousel-item active shadow-sm rounded p-4 mb-5">
                 <div class="testi-author-info align-items-center">
                   <img src="../NewSkills/Nuxt.png" alt="seo" class="w-55 h-55 img-thumbnail shadow-sm">
                   <div class="author ms-3">
                     <h3 class="h3 fs-6 mb-1">{{textNameNewSOneH3}}</h3>
                     <p class="text-muted m-0">{{textNewIntroducedP}}</p>
                   </div>
                </div>
                <p class="text-muted mt-3">{{ textNewDescriptionP }}</p>
               </div>
 </template>
 
 <script>
 export default {
     data(){
     return{
         textNameNewSOneH3:'Nuxt',
         textNewIntroducedP:'The Intuitive Vue Framework',
         textNewDescriptionP:'Nuxt is an open source framework that makes web development intuitive and powerful. Create performant and production-grade full-stack web apps and websites with confidence.'
     }
  }
 }
 </script>
 
 <style>
 
 </style>