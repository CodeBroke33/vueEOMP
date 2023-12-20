<template>
  <nav class="navbar navbar-expand-lg bg-body-tertiary">
  <div class="container-fluid">
   <router-link to="/">
        <img class="img-fluid"  src="https://lh3.googleusercontent.com/u/0/drive-viewer/AEYmBYRd_KY4JPDxA86ZH1G9Uh0cWxivl3bEDI43QGsxE4K6xZzhWWflCNPgbRw7lQBsl1ubZxXyM0uEfA0TC53v9W_XMoQmrQ=w857-h892" alt="logo">
   </router-link>
    <div class="collapse navbar-collapse" id="navbarNav">
      <ul class="navbar-nav">
        <li class="nav-item">
          <router-link to="/">
            Home
          </router-link>
        </li>
        <li class="nav-item">
          <router-link to="/about">
            About
          </router-link>
        </li>
        <li class="nav-item">
            <router-link to="/resume">
            Resume
          </router-link>
        </li>
        <li class="nav-item">
            <router-link to="/project">
            Projects
          </router-link>
        </li>
        <li class="nav-item">
            <router-link to="/testimonial">
            Testimonial
          </router-link>
        </li>
        <li class="nav-item">
            <router-link to="/reachme">
            Reach Me
          </router-link>
        </li>
       
      </ul>
    </div>
  </div>
</nav>
</template>

<script>
    export default {
        data(){
            return
        }
    }
</script>

<style scoped>

</style>