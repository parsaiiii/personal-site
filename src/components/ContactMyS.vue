<template>
    <div class="contact">
        <section class="contact py-5" id="contact">
        <div class="container-lg py-4">
          <div class="row justify-content-center">
            <div class="col-lg-8 ">
                <div class="section-title text-center">
                    <h2 class="h2 fw-bold mb-5">{{ textContactH2 }}</h2>
      </div>
     </div>
   </div>
   <div class="row">
    <div class="col-mb-5">
         <Emile></Emile>
         <Phone></Phone>
    </div>
    <Form> </Form>
   </div>
 </div>
</section>
</div> 
</template>

<script>
import Emile from './Contact/ContactEmile.vue';
import Phone from './Contact/ContactPhon.vue';
import Form from './Contact/ContactForm.vue';
export default {
    components:{Emile , Phone , Form},
  data(){
    return{
        textContactH2:'Contact Me'
    }
  }
}
</script>

<style>

</style>