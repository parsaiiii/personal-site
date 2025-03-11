<template>
  <div class="my-skills">
    <section class="Freelancer-Available bg-secondary py-5">
        <div class="container-lg py-4">
            <div class="row justify-content-center">
                <div class="col-lg-8 text-center">
                    <p class="text-light fs-5">{{textSkillsAreP}}</p>
                    <h2 class="h2 fs-1 text-white mb-4">{{textSkillsYesH2}}</h2>
                    <a href="#contact" class="btn btn-outline-light">{{ textBtnA }}</a>
                </div>
            </div>
      </div>
  </section>
</div>
</template>

<script>
export default {
  data(){
    return{
        textSkillsAreP:'Are there any other skills you want to acquire?',
        textSkillsYesH2:"Yes, I want to get these",
        textBtnA:'My new skills'        
    }
  }
}
</script>

<style>

</style>