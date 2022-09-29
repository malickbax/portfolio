<template>
  <header id="header" class="navbar navbar-expand-lg navbar-end navbar-sticky-top navbar-light bg-white shadow-lg "
    data-hs-header-options='{
      "fixMoment": 1000,
      "fixEffect": "slide"
      }'>
  <div class="container">
    <nav class="js-mega-menu navbar-nav-wrap">
<!-- My name/logo here -->
      <a href="./index.html" class="btn btn-primary btn-transition">Malick Ba</a>
<!-- End name/logo -->

<!-- POTENTIAL DROP DOWN MENU FOR FUTURE VERSIONS OF PORTFOLIO WEBSITE -->
  <!-- <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNavDropdown" aria-controls="navbarNavDropdown" aria-expanded="false" aria-label="Toggle navigation">
    <span class="navbar-toggler-default">
      <i class="bi-list"></i>
    </span>
    <span class="navbar-toggler-toggled">
      <i class="bi-x"></i>
    </span>
  </button> -->
<!-- End potential drop down menu -->

<!-- Menu -->
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
            <li class="nav-item">
              <a href="#resume" class="nav-link">Resume</a>
            </li>
            <li class="nav-item">
              <a href="#contact" class="nav-link">Contact</a>
            </li>
          </ul>
        </div>
      </div>
<!-- End Menu -->
      </nav>
    </div>
  </header>
</template>

<script>
export default {
    name: 'NavBar',
}
</script>