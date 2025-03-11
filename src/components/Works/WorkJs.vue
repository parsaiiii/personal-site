<template>
    <div class="col-md-6 col-lg-4 ">
               <div class="portfolio-item">
                 <img src="../Works/javascriptI.jpg" alt="html item" class="w-100 img-thumbnail shadow-sm">
                 <h3 class="h3 text-capitalize fs-5 my-2">{{textNameH3}}</h3>
                 <p class="mb-4"><a class="text-secondary text-decoration-none" href="#">{{ textCapshinP }}</a></p> 
               </div>
             </div>
 </template>
<script>
export default { 
    data(){
  return{
    textNameH3:'JAVASCRIPT',
    textCapshinP:'JS'
  }
 }
}
</script>

<style>

</style>