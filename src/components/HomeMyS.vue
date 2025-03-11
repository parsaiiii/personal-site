<template>
  <div class="home-me">
    <section class="home py-5" id="home">
        <div class="container-lg">
            <div class="row  min-vh-100 align-items-center align-content-center">
                <div class="col-md-6 mt-5 mt-md-0">
                    <div class="home-img text-center shadow-sm">
                        <!-- profile -->
                        <img class=" img-thumbnail shadow-sm" src="../assets/img/Profile.jpg" alt="Profile">
                    </div>
                </div>
                <div class="col-md-6 order-md-first mt-5 mt-md-0">
                    <div class="home-text">
                        <p class="text-muted mb-1">{{ textHomeP }}</p>
                        <h1 class="h1 text-secondary text-uppercase fs-1 fw-bold">{{ textHomeH1 }}</h1>
                        <h1 class="h1 fs-4">{{ textHomeMyName }}</h1>
                        <p class="mt-4 text-muted">{{ textHomeDescription }}</p>
                        <a href="#portfolio" class="btn btn-outline-secondary px-3 mt-3">{{ textHomeBtn }}</a>
                    </div>
                </div>
            </div>
        </div>
    </section>
  </div>
</template>
 
<script>
export default {
    name:'HomeMyS',
  data(){
    return{
        textHomeP:"Hello I'm",
        textHomeH1:'Web Programming',
        textHomeMyName:'Parsa Easy',
        textHomeDescription:'I Am From Iran And I Am Seventeen Years Old And I Have Been Programming For About eight Months',
        textHomeBtn:'My Work'
    }
  }
}
</script>

<style>

</style>