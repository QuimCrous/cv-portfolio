<template>
  <!-- Start Banner 
      ============================================= -->
  <div class="auto-height bg-fixed banner-style-one">
    <div class="container">
      <div class="double-items">
        <div class="row align-center">
          <div class="col-lg-6 info">
            <h1 class="text-invisible">WELCOME</h1>
            <h2>
              Hey <img src="../assets/img/shape/4.png" alt="Icon" /> We're
              <span>Quim and Adrià</span>
            </h2>
            <h3 class="title">
              <span class="header-caption" id="page-top">
                <!-- type headline start-->
                <span class="cd-headline clip is-full-width">
                  <!-- ROTATING TEXT -->
                  <span class="cd-words-wrapper" :key="key">
                    <b class="is-visible"
                      >Fullstack Developer and 3D designer</b
                    >
                    <b class="is-hidden">Professional Coder</b>
                    <b class="is-hidden">Backend and Design Lovers</b>
                  </span>
                </span>
                <!-- type headline end -->
              </span>
            </h3>
            <div class="button mt-55">
              <a class="btn btn-md circle btn-dark" href="#resume">My Resume</a>
            </div>
          </div>

          <div class="col-lg-6 thumb" data-wow-delay="900ms">
            <img
              class="wow fadeInDown"
              src="../assets/img/illustration/1.png"
              alt="Thumb"
            />
            <div class="shape-center">
              <img src="../assets/img/shape/7.png" alt="Thumb" />
            </div>
          </div>
        </div>
        <div class="personal-social">
          <ul>
            <li class="facebook">
              <a href="#">
                <i class="fab fa-facebook-f"></i>
              </a>
            </li>
            <li class="behance">
              <a href="#">
                <i class="fab fa-behance"></i>
              </a>
            </li>
            <li class="dribbble">
              <a href="#">
                <i class="fab fa-dribbble"></i>
              </a>
            </li>
          </ul>
        </div>
      </div>
    </div>
  </div>
  <!-- End Banner -->
</template>

<script>
export default {
  data: function () {
    return {
      key: Math.random(),
    };
  },
  mounted: function () {
    //console.log(this);
    jQuery(document).ready(function (d) {
      initTyping(d);
    });
  },
};
</script>

<style scoped></style>
