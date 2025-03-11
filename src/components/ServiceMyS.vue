<template>
   <section class="services  py-5" id="services">
    <div class="container-lg py-4">
        <div class="row justify-content-center">
            <div class="col-lg-8 ">
                <div class="section-title text-center">
                    <h2 class="h2 fw-bold mb-5">{{textServisWH2}}</h2>
                </div>
            </div>
        </div>
        <div class="row text-center">
            <BoxServisDiv></BoxServisDiv>

       <BoxServisDes></BoxServisDes>
       <BoxServesPhoto></BoxServesPhoto>
       </div>
    </div>
   </section>
</template>

<script>
import BoxServisDiv from './Service/BoxServisDiv.vue';
import BoxServisDes from './Service/BoxServisDes.vue';
import BoxServesPhoto from './Service/BoxServesPhoto.vue';
export default {
name:'ServiceMyS',
components:{BoxServisDiv , BoxServisDes , BoxServesPhoto},
data(){
    return{
        textServisWH2:'What I Do'
    }
}
}
</script>

<style>

</style>