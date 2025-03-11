<template>
<div class="bg-light">
  <div class="box">

    <!--    startNavbar   -->
    <Navbar class="bg-body-tertiary  sticky-top"></Navbar>
    <!--    endNavbar     -->

    <!--    startHome     -->
    <Home></Home>
     <!--   endtHome      -->

     <!--   startAbout    -->
     <About></About>
      <!--    endAbout    -->

      <!--    startService -->
      <Service></Service>
      <!--    startService -->

      <!--   startWorks -->
      <Work></Work>
      <!--   endWorks -->

      <!--    startOther Skills  -->
      <Skills></Skills>
      <!--    endOther Skills    -->

       <!--    start New Skills  -->
       <NewSkills></NewSkills>
      <!--    end New Skills    -->

        <!--   start Contact  -->
        <Contact></Contact>
      <!--    end Contact    -->

        <!--   start Footer  -->
        <Footer></Footer>
       <!--    end Footer    -->
  </div>
</div>
</template>
<script>
import Navbar from './components/NavbarMyS.vue'
import Home from './components/HomeMyS.vue'
import About from './components/AboutMyS.vue'
import Service from './components/ServiceMyS.vue'
import Work from './components/WorkMyS.vue'
import Skills from './components/SkillsMyS.vue'
import NewSkills from './components/NewSkillsMyS.vue'
import Contact from './components/ContactMyS.vue'
import Footer from './components/FooterMyS.vue'
export default {
  name:'App',
  components:{Navbar , Home , About , Service , Work , Skills , NewSkills , Contact , Footer},
  data(){
    return{

    }
  }
}
</script>
<style>
</style>
