<template>
  <footer class="footer border-top py-4">
    <div class="container-lg">
        <div class="row">
            <div class="col-lg-12">
                <p class="m-0 text-center text-muted ">&copy; {{ numberYears }} Personal Site</p>
            </div> 
      </div>
    </div>
  </footer>
</template>

<script>
export default {
 data(){
    return{
        numberYears:2025,
        textResults:'Personal Site'
    }
 }
}
</script>

<style>

</style>