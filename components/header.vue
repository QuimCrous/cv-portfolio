<template>
  <div>
    <header id="home">
      <!-- Start Navigation -->
      <nav
        class="navbar mobile-sidenav onepage-menu mobile-nav-only attr-border navbar-sticky navbar-default validnavs navbar-fixed dark no-background"
      >
        <div
          class="container d-flex justify-content-between align-items-center"
        >
          <!-- Start Header Navigation -->
          <div class="navbar-header">
            <button
              type="button"
              class="navbar-toggle"
              data-toggle="collapse"
              data-target="#navbar-menu"
            >
              <i class="fa fa-bars"></i>
            </button>
            <a class="navbar-brand" href="index.html">
              <img src="../assets/img/logo.png" class="logo" alt="Logo" />
            </a>
          </div>
          <!-- End Header Navigation -->

          <!-- Collect the nav links, forms, and other content for toggling -->
          <div class="collapse navbar-collapse" id="navbar-menu">
            <img src="../assets/img/logo.png" alt="Logo" />
            <button
              type="button"
              class="navbar-toggle"
              data-toggle="collapse"
              data-target="#navbar-menu"
              @click="collapsedNav"
            >
              <i class="fa fa-times"></i>
            </button>

            <ul
              class="nav navbar-nav navbar-right"
              data-in="fadeInDown"
              data-out="fadeOutUp"
            >
              <li>
                <a class="smooth-menu" href="#home">Home</a>
              </li>
              <li>
                <a class="smooth-menu" href="#expertise">expertise</a>
              </li>
              <li>
                <a class="smooth-menu" href="#portfolio">portfolio</a>
              </li>
              <li>
                <a class="smooth-menu" href="#about">about</a>
              </li>
              <li>
                <a class="smooth-menu" href="#blog">blog</a>
              </li>
              <li>
                <a class="smooth-menu" href="#contact">contact</a>
              </li>
            </ul>
          </div>
          <!-- /.navbar-collapse -->

          <!-- Main Nav -->
        </div>
        <!-- Overlay screen for menu -->
        <div class="overlay-screen"></div>
        <!-- End Overlay screen for menu -->
      </nav>
      <!-- End Navigation -->
    </header>
    <!-- End Header -->

    <!-- Start Header Fixed 
    ============================================= -->
    <header class="header-fixed">
      <div class="f-flex">
        <div class="logo">
          <a href="#home"
            ><img src="../assets/img/logo-icon.png" alt="Logo"
          /></a>
        </div>
        <div class="menu">
          <ul class="nav">
            <li>
              <a class="smooth-menu" href="#home">
                <i class="fas fa-home"></i>
                <div class="menu-name">Home</div>
              </a>
              <!-- <NuxtLink to="/">
                <i class="fas fa-home"></i>
                <div class="menu-name">Home</div>
              </NuxtLink> -->
            </li>
            <li>
              <a class="smooth-menu" href="#services">
                <i class="fas fa-cog"></i>
                <div class="menu-name">Services</div>
              </a>
            </li>
            <li>
              <a class="smooth-menu" href="#portfolio">
                <i class="fas fa-briefcase"></i>
                <div class="menu-name">Portfolio</div>
              </a>
            </li>
            <li>
              <a class="smooth-menu" href="#about">
                <i class="fas fa-user"></i>
                <div class="menu-name">About</div>
              </a>
            </li>
            <li>
              <!-- <a class="smooth-menu" href="#resume">
                <i class="fas fa-file-alt"></i>
                <div class="menu-name">Resume</div>
              </a> -->
              <NuxtLink to="/blog">
                <i class="fas fa-file-alt"></i>
                <div class="menu-name">Blog</div>
              </NuxtLink>
            </li>
            <li>
              <a class="smooth-menu" href="#contact">
                <i class="fas fa-comments"></i>
                <div class="menu-name">Contact</div>
              </a>
            </li>
          </ul>
        </div>
        <div class="video">
          <a
            href="https://www.youtube.com/watch?v=5qRsGTuy3Rs"
            class="popup-youtube video-play-button theme"
          >
            <i class="fas fa-play"></i>
          </a>
        </div>
      </div>
    </header>
    <!-- End Header Fixed -->
  </div>
</template>

<script setup></script>

<style lang="scss" scoped></style>
