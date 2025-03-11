<template>
   <div class="col-md-6 mt-5 mt-md-0">
              <div class="skill-item mb-4">
                <h3 class="h3 fs-6">{{textAbFLangH3Career1Ht}}</h3>
                <div class="progress" role="progressbar" aria-label="Example 1px high" aria-valuenow="100" aria-valuemin="0" aria-valuemax="100" style="height: 5px">
                  <div class="progress-bar bg-secondary" style="width: 100%"></div>
                </div>
               </div>
               <div class="skill-item mb-4">
                  <h3 class="h3 fs-6">{{textAbFLangH3Career2Cs}}</h3>
                  <div class="progress" role="progressbar" aria-label="Example 1px high" aria-valuenow="70" aria-valuemin="0" aria-valuemax="100" style="height: 5px">
                    <div class="progress-bar bg-secondary" style="width: 98%"></div>
                  </div>
               </div>
               <div class="skill-item mb-4">
                 <h3 class="h3 fs-6">{{textAbFLangH3Career3Js}}</h3>
                <div class="progress" role="progressbar" aria-label="Example 1px high" aria-valuenow="85" aria-valuemin="0" aria-valuemax="100" style="height: 5px">
                  <div class="progress-bar bg-secondary" style="width: 95%"></div>
                </div>
              </div>
              
              <div class="skill-item mb-4">
                 <h3 class="h3 fs-6">{{textAbFLangH3Career4Jq}}</h3>
                 <div class="progress" role="progressbar" aria-label="Example 1px high" aria-valuenow="90" aria-valuemin="0" aria-valuemax="100" style="height: 5px">
                   <div class="progress-bar bg-secondary" style="width: 90%"></div>
                 </div>
                </div>
            
            <div class="skill-item mb-4">
              <h3 class="h3 fs-6">{{textAbFLangH3Career4Bt}}</h3>
                <div class="progress" role="progressbar" aria-label="Example 1px high" aria-valuenow="85" aria-valuemin="0" aria-valuemax="100" style="height: 5px">
                  <div class="progress-bar bg-secondary" style="width: 95%"></div>
                </div>
                </div>
                <div class="skill-item mb-4">
                 <h3 class="h3 fs-6">{{textAbFLangH3Career4Vu}}</h3>
                 <div class="progress" role="progressbar" aria-label="Example 1px high" aria-valuenow="90" aria-valuemin="0" aria-valuemax="100" style="height: 5px">
                   <div class="progress-bar bg-secondary" style="width: 93%"></div>
                 </div>
                </div>
             
              </div>
</template>

<script>
export default {
    name:'AbFlattend',
    data(){
        return{
            textAbFLangH3Career1Ht:'HTML',
            textAbFLangH3Career2Cs:'CSS',
            textAbFLangH3Career3Js:'JAVA SCRIPT',
            textAbFLangH3Career4Jq:'JQUERY',
            textAbFLangH3Career4Bt:'BOOTSTRAP',
            textAbFLangH3Career4Vu:'VUE',
        }
    }

}
</script>

<style>

</style>