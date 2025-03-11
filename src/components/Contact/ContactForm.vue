<template>
   <div class="col-md-7">
    <div class="contact-form">
        <form>
                  <div class="row">
                    <div class="col-lg-6 mb-4">
                      <input type="text" placeholder="Your Name " class="form-control form-control-lg fs-6 border-0 shadow-sm">
                    </div>
                    <div class="col-lg-6 mb-4">
                      <input type="text" placeholder="Your Email " class="form-control form-control-lg fs-6 border-0 shadow-sm">
                    </div>
                  </div>
                  <div class="row">
                    <div class="col-lg-12 mb-4">
                      <input type="text" placeholder="Subject " class="form-control form-control-lg fs-6 border-0 shadow-sm">
                    </div>
                  </div>
                  <div class="row">
                    <div class="col-lg-12 mb-4">
                      <textarea placeholder="Your Message" rows="5" class="form-control form-control-lg fs-6 border-0 shadow-sm"></textarea>
                    </div>
                  </div>
                  <div class="row">
                    <div class="col-lg-12">
                      <button type="submit" class="btn btn-outline-secondary px-3">{{ textBtnForm }}</button>
                    </div>
                  </div>
                </form>
        </div>
    </div>
</template>

<script>
export default {
  data(){
    return{
        textBtnForm:'Send message'
    }
  }
}
</script>

<style>

</style>