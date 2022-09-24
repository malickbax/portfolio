<template>
    <header id="header" class="navbar navbar-expand-lg navbar-end navbar-sticky-top navbar-light bg-white shadow-lg "
          data-hs-header-options='{
            "fixMoment": 1000,
            "fixEffect": "slide"
          }'>
    <div class="container">
      <nav class="js-mega-menu navbar-nav-wrap">
        <!-- Default Logo -->
          <a href="./index.html" class="btn btn-primary btn-transition">Malick Ba</a>
     
        <!-- End Default Logo -->

        <!-- Toggler -->
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNavDropdown" aria-controls="navbarNavDropdown" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-default">
            <i class="bi-list"></i>
          </span>
          <span class="navbar-toggler-toggled">
            <i class="bi-x"></i>
          </span>
        </button>
        <!-- End Toggler -->
      
        <!-- Collapse -->
        <div class="collapse navbar-collapse" id="navbarNavDropdown">
          <div class="navbar-absolute-top-scroller">
            <ul class="navbar-nav">

            <li class="nav-item">
              <a href="./index.html" class="nav-link">Home</a>
            </li>


            <li class="nav-item">
              <a href="#about" class="nav-link">About</a>
            </li>

            <li class="nav-item">
              <a href="#projects" class="nav-link">Projects</a>
            </li>
          <!-- Projects -->
          <!-- <li class="nav-item dropdown">
            <a id="companyMegaMenu" class="nav-link dropdown-toggle " href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false">Projects</a> -->

            <!-- Projects Menu -->
            <!-- <div class="dropdown-menu" aria-labelledby="companyMegaMenu" style="min-width: 14rem;">
              <a class="dropdown-item" href="#">API - Terrorism Data Center</a>
              <a class="dropdown-item" href="#">Blog - Bragging Rights</a>
              <a class="dropdown-item" href="#">e-Commerce - Run Buddy</a>
              <a class="dropdown-item" href="#">Employee Teams Generator</a>
              <a class="dropdown-item" href="#">Fooder</a>
              <a class="dropdown-item" href="#">Weather Locator</a>
              <a class="dropdown-item" href="#">Workday Planner</a>
              <a class="dropdown-item" href="#">Horiseon - Commercial Business</a>
              <a class="dropdown-item" href="#">Secure Password Generator</a>
              <a class="dropdown-item" href="#">Regex Tutorial</a>
              <a class="dropdown-item" href="#">Portfolio Generator</a>
            </div>

          </li> -->

          <!-- ADD RESUME LATER -->
          <!-- <li class="nav-item">
                <a class="nav-link">Resumé</a>
          </li> -->

              <li class="nav-item">
                <a href="#contact" class="nav-link">Contact</a>
              </li>

            </ul>
          </div>
        </div>
        <!-- End Collapse -->
      </nav>
    </div>
  </header>

</template>
<script>
export default {
    name: 'NavBar',
}
</script>
<style>
</style>