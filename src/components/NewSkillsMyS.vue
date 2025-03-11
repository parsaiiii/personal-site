<template>
  <div class="newSkills">
    <section class="Other-skills py-5" id="Newskills">
        <div class="container-lg py-4">
           <div class="row justify-content-center">
            <div class="col-lg-8 ">
                <div class="section-title text-center">
                    <h2 class="h2 fw-bold mb-5">{{ textNameNewSkills }}</h2>
                  </div>
                </div>
            </div> 
            <div class="row justify-content-center ">
            <div class="col-lg-8 col-xl-7 ">
              <div id="carousel1" class="carousel slide">
                <div class="carousel-indicators">
               <button type="button" data-bs-target="#carousel1" data-bs-slide-to="0" class="active bg-secondary" aria-current="true" aria-label="Slide 1"></button>
                <button type="button" data-bs-target="#carousel1" data-bs-slide-to="1" aria-label="Slide 2" class="bg-secondary"></button>
               <button type="button" data-bs-target="#carousel1" data-bs-slide-to="2" aria-label="Slide 3" class="bg-secondary"></button>
          </div> 
          <div class="carousel-inner p-1">
            <NewSkillsOne></NewSkillsOne>
            <NewSkillsTwo></NewSkillsTwo>
            <NewSkillsThree></NewSkillsThree>
          </div>
        </div>
        </div>
      </div>
   </div>
   </section>
  </div>
</template>

<script>
import NewSkillsOne from './NewSkills/NewSkillsOne.vue'
import NewSkillsTwo from './NewSkills/NewSkillsTwo.vue'
import NewSkillsThree from './NewSkills/NewSkillsThree.vue'
export default {
    components:{NewSkillsOne , NewSkillsTwo , NewSkillsThree},
 data(){
    return{
        textNameNewSkills:'New Skills'
    }
 }
}
</script>

<style>

</style>