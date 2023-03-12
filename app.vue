<template>
  <NuxtPage />
  <Footer />
</template>

<script setup>
import Index from "./pages/index.vue";
import Navigation from "./components/header.vue";
import Footer from "./components/footer.vue";
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
