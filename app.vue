import Pages from './pages/index.vue';

<template>
  <Navigation />
  <div>
    <Index />
  </div>
</template>

<script setup>
import Index from "./pages/index.vue";
import Navigation from "./pages/header.vue";
useHead({
  script: [
    {
      src: "/assets/js/jquery-3.6.0.min.js",
      body: true,
    },
    { src: "/assets/js/bootstrap.bundle.min.js", body: true },
    { src: "/assets/js/jquery.appear.js", body: true },
    { src: "/assets/js/jquery.easing.min.js", body: true },
    { src: "/assets/js/jquery.magnific-popup.min.js", body: true },
    { src: "/assets/js/modernizr.custom.13711.js", body: true },
    { src: "/assets/js/swiper-bundle.min.js", body: true },
    { src: "/assets/js/wow.min.js", body: true },
    { src: "/assets/js/progress-bar.min.js", body: true },
    { src: "/assets/js/circle-progress.js", body: true },
    { src: "/assets/js/isotope.pkgd.min.js", body: true },
    { src: "/assets/js/imagesloaded.pkgd.min.js", body: true },
    { src: "/assets/js/jquery.nice-select.min.js", body: true },
    { src: "/assets/js/count-to.js", body: true },
    { src: "/assets/js/jquery.scrolla.min.js", body: true },
    { src: "/assets/js/YTPlayer.min.js", body: true },
    { src: "/assets/js/TweenMax.min.js", body: true },
    { src: "/assets/js/typed.js", body: true },
    { src: "/assets/js/validnavs.js", body: true },
    { src: "/assets/js/main.js", body: true },
  ],
});
</script>

<script>
export default {
  mounted: function () {},
};
// export default {
//   plugins: [
//     "/assets/js/jquery-3.6.0.min.js",
//
//   ],
// };
</script>
