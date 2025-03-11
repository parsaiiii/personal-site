<template>
   <div class="testi-item bg-white carousel-item active shadow-sm rounded p-4 mb-5">
                <div class="testi-author-info align-items-center">
                  <img src="../NewSkills/Vite.png" alt="seo" class="w-55 h-55 img-thumbnail shadow-sm">
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
        textNameNewSOneH3:'Vite',
        textNewIntroducedP:'The Build Tool for the Web',
        textNewDescriptionP:'Vite is a blazing fast frontend build tool powering the next generation of web applications.'
    }
 }
}
</script>

<style>

</style>