<template>
    <div class="contact-item d-flex mb-3">
     <div class="contact-item d-flex mb-3">
         <div class="icon fs-4 text-secondary">
          <svg xmlns="http://www.w3.org/2000/svg" width="25" height="25" fill="currentColor" class="bi bi-phone" viewBox="0 0 16 16">
           <path d="M11 1a1 1 0 0 1 1 1v12a1 1 0 0 1-1 1H5a1 1 0 0 1-1-1V2a1 1 0 0 1 1-1zM5 0a2 2 0 0 0-2 2v12a2 2 0 0 0 2 2h6a2 2 0 0 0 2-2V2a2 2 0 0 0-2-2z"/>
           <path d="M8 14a1 1 0 1 0 0-2 1 1 0 0 0 0 2"/>
          </svg>
                    
   </div>
   <div class="text ms-3">
     <h3 class="h3 fs-5">{{textConEmiName}}</h3>
     <p class="text-muted">{{ numberTelMy }}</p>
   </div>
 </div>
 </div>
 </template>
 
 <script>
 export default {
   data(){
     return{
         textConEmiName:'Phone',
         numberTelMy:'0938 329 2562'
     }
   }
 }
 </script>
 
 <style>
 
 </style>