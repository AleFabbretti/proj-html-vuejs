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
    <div class="d-flex align-items-center">
      <img src="../assets/dark-logo.png" alt="logo" />
    </div>
    <div class="d-flex align-items-center">
      <i class="fa-solid fa-cart-shopping"></i>
      <i class="fa-regular fa-user"></i>
      <div class="search-container">
        <form>
          <input
            class="search"
            type="text"
            placeholder="Search.."
            name="search"
          />
          <button type="submit">
            <i class="fa-solid fa-magnifying-glass"></i>
          </button>
        </form>
      </div>
    </div>
  </div>
</template>

<style lang="scss" scoped>
img {
  width: 180px;
  height: 25px;
}
.search {
  border: none;
  background-color: white;
  margin-left: 30px;
}

button {
  border: none;
  background-color: white;
  & i {
    color: #20aea5;
  }
}

i {
  margin-left: 20px;
}
</style>
