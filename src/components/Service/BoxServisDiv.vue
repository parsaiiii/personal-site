<template>
 
            <div class="col-md-6 col-lg-4 mb-4">
              <div class="service-item shadow-sm p-4 rounded bg-white">
                <div class="icon my-3 text-secondary fs-2">
                    <svg xmlns="http://www.w3.org/2000/svg" width="40" height="40" fill="currentColor" class="bi bi-code-slash" viewBox="0 0 16 16">
                    <path d="M10.478 1.647a.5.5 0 1 0-.956-.294l-4 13a.5.5 0 0 0 .956.294zM4.854 4.146a.5.5 0 0 1 0 .708L1.707 8l3.147 3.146a.5.5 0 0 1-.708.708l-3.5-3.5a.5.5 0 0 1 0-.708l3.5-3.5a.5.5 0 0 1 .708 0m6.292 0a.5.5 0 0 0 0 .708L14.293 8l-3.147 3.146a.5.5 0 0 0 .708.708l3.5-3.5a.5.5 0 0 0 0-.708l-3.5-3.5a.5.5 0 0 0-.708 0"/>
                  </svg>
                </div>
                <h3 class="h3 fs-5 py-2">{{textBoxWeb}}</h3>
                <p class="text-muted">{{textBowLorem}} </p>
           </div>
       </div>

</template>

<script>
export default {
name:'BoxServisDiv',
data(){
    return{
        textBoxWeb:'Web Development',
        textBowLorem:'Lorem ipsum dolor sit amet consectetur adipisicing elit. '
    }
}
}
</script>

<style>

</style>