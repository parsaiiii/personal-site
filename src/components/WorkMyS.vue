<template>
  <section class="portfolio  py-5" id="portfolio">
        <div class="container-lg py-4">
          <div class="row justify-content-center">
            <div class="col-lg-8 ">
                <div class="section-title text-center">
                    <h2 class="h2 fw-bold mb-5">{{textWork}}</h2>
                </div>
            </div>
        </div>
        <div class="row">
          <Htmls></Htmls>
          <Css></Css>
          <Js></Js>
          <Jquery></Jquery>
          <Bootstrap></Bootstrap>
          <Vue></Vue>
        </div>
    </div>
   </section>       
</template>

<script>
import Htmls from '../components/Works/WorkHtml.vue'
import Css from '../components/Works/WorkCss.vue'
import Js from '../components/Works/WorkJs.vue'
import Jquery from '../components/Works/WorkJq.vue'
import Bootstrap from '../components/Works/WorkBoot.vue'
import Vue from '../components/Works/WorkVue.vue'
export default {
components:{Htmls , Css , Js , Jquery , Bootstrap , Vue},
data(){
    return{
        textWork:'Latest Works'
    }
}
}
</script>

<style>

</style>