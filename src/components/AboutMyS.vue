<template>
  <section class="about  py-5" id="about">
        <div class="container-lg py-4">
          <div class="row justify-content-center">
            <div class="col-lg-8 ">
              <div class="section-title text-center">
                <h2 class="h2 fw-bold mb-5">{{ textAboutH2 }}</h2>
              </div>
            </div>
          </div>
          <div class="row">
            <div class="col-md-6">
            <div class="about-text">
              <h3 class="h3 fs-4 mb-3">
               {{ textAboutDescriptionH3 }}
                
              </h3>
              <p class="text-muted">
              {{ textAboutLoremP }}
              </p>
            </div>
            <div class="row text-center text-uppercase my-3">
              <div class="col-sm-4">
                <div class="fact-item">
                  <h4 class="h4 fs-1 fw-bold">{{ numberAboutH41 }}</h4>
                  <p class="text-muted">{{textAboutProjectP1}}</p>
                </div>
              </div>
              <div class="col-sm-4">
                <div class="fact-item">
                  <h4 class="h4 fs-1 fw-bold">{{ numberAboutH42 }}</h4>
                  <p class="text-muted">{{ textAboutProjectP2 }}</p>
                </div>
              </div>
              <div class="col-sm-4">
                <div class="fact-item">
                  <h4 class="h4 fs-1 fw-bold">{{ numberAboutH43 }}</h4>
                  <p class="text-muted">{{ textAboutProjectP3 }}</p>
                </div>
              </div>
            </div>
            <BtnLink></BtnLink>
            </div>
            </div>
            <Flattened></Flattened>
           </div>
       </section>
</template>

<script>
import BtnLink from './Abouts/BtnLinkAbout.vue'
import Flattened from './Abouts/AbFlattened.vue'
export default {
    name:'AboutMyS',
     components:{BtnLink , Flattened},
   data(){
    return{
       textAboutH2:'About Me',
       textAboutDescriptionH3:'I have professional work experience and front-end knowledge',
       textAboutLoremP:'Lorem ipsum dolor sit amet consectetur adipisicing elit. porro non facilis, doloribus a possimus ad quaerat. Dignissimos quos',
       numberAboutH41:100,
       textAboutProjectP1:'Projects Completed',
       numberAboutH42:90,
       textAboutProjectP2:'Happy Clients',
       numberAboutH43:95,
       textAboutProjectP3:'Positive Reviews ',
    }
 }
}
</script>

<style>

</style>