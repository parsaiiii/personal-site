<template>
  <div class="col-md-6 col-lg-4 mb-4">
    <div class="service-item shadow-sm p-4 rounded bg-white">
                <div class="icon my-3 text-secondary fs-2">
                  <svg xmlns="http://www.w3.org/2000/svg" width="40" height="40" fill="currentColor" class="bi bi-code-slash" viewBox="0 0 16 16">
                    <path d="M6.002 5.5a1.5 1.5 0 1 1-3 0 1.5 1.5 0 0 1 3 0"/>
                    <path d="M2.002 1a2 2 0 0 0-2 2v10a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V3a2 2 0 0 0-2-2zm12 1a1 1 0 0 1 1 1v6.5l-3.777-1.947a.5.5 0 0 0-.577.093l-3.71 3.71-2.66-1.772a.5.5 0 0 0-.63.062L1.002 12V3a1 1 0 0 1 1-1z"/>
                  </svg>
                </div>
                <h3 class="h3 fs-5 py-2">{{ textBoxServisPhotoH3 }}</h3>
                <p class="text-muted">{{ textBoxServisPhotoPLorem }} </p>
  </div></div>
</template>

<script>
export default {
 data(){
    return{
        textBoxServisPhotoH3:'Photoshop',
        textBoxServisPhotoPLorem:'Lorem ipsum dolor sit amet consectetur adipisicing elit.'
    }
 }
}
</script>

<style>

</style>