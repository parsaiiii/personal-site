<template>
    <div class="navbar-my">
      <nav class="navbar bg-body-tertiary navbar-light bg-light shadow-sm sticky-top opacity-0.69 bd-navbar ">
        <div class="container-lg">
          <h2 class="navbar-brand h2 text-secondary fw-bold fs-4">{{ textNavbarH2 }}</h2>
          <div class="dropdown">
            <button class="btn btn-outline-secondary px-3" id="dropdownMenuButton" data-bs-toggle="dropdown" aria-ewpanded="false">
              <span class="navbar-toggler-icon"></span>
            </button>
            <ul class="dropdown-menu dropdown-menu-end" aria-labelledby="dropdownMenuButton">
              <li><a class="dropdown-item" href="#home">{{ textNavbarLi1 }}</a></li>
              <li><a class="dropdown-item" href="#about">{{ textNavbarLi2 }}</a></li>
              <li><a class="dropdown-item" href="#services">{{ textNavbarLi3 }}</a></li>
              <li><a class="dropdown-item" href="#portfolio">{{ textNavbarLi4 }}</a></li>
              <li><a class="dropdown-item" href="#Newskills">{{ textNavbarLi5 }}</a></li>
              <li><a class="dropdown-item" href="#contact">{{ textNavbarLi6 }}</a></li>
            </ul>
          </div>
        </div>
      </nav>
    </div>
</template>

<script>
export default {
    name:'NavbarMyS',
    data(){
      return{
        textNavbarH2:'P.E',
        textNavbarLi1:'Home',
        textNavbarLi2:'About',
        textNavbarLi3:'Services',
        textNavbarLi4:'Portfolio',
        textNavbarLi5:'New skills',
        textNavbarLi6:'Contact'
      }
    }
}
</script>

<style>

</style>