<script>
import HeaderNav from "./HeaderNav.vue";
export default {
  name: "AppHeader",
  components: {
    HeaderNav,
  },
};
</script>

<template>
  <div class="container d-flex justify-content-between">
    <HeaderNav />
    <ul class="d-flex align-items-center">
      <li class="mx-3">Home</li>
      <li class="mx-3">Pages</li>
      <li class="mx-3">Courses</li>
      <li class="mx-3">Features</li>
      <li class="mx-3">Blog</li>
      <li class="mx-3">Shop</li>
    </ul>
    <div>
      <img src="../assets/dark-logo.png" alt="logo" />
    </div>
    <div class="d-flex">
      <i class="fa-solid fa-cart-shopping"></i>
      <div>
        <i class="fa-regular fa-user"></i>
      </div>
    </div>
  </div>
</template>

<style lang="scss" scoped></style>
