<script>
export default {
  name: "HeroMainTop",
};
</script>

<template>
  <div class="hero d-flex align-items-center justify-content-center">
    <div class="description d-block text-center">
      <h3>Commence Business</h3>
      <h1>Distant Mentoring Program</h1>
      <button class="px-4 py-2 mt-3" type="submit">
        Download free guidebook
        <i class="fa-solid fa-arrow-right mx-2"></i>
      </button>
    </div>
  </div>
</template>

<style lang="scss" scoped>
.hero {
  background-image: url(./src/assets/home-3-hero-bg.jpg);
  height: 600px;
  background-size: cover;
  background-repeat: no-repeat;
  & .description {
    color: white;
    & h1 {
      font-size: 50px;
    }
    & button {
      border: none;
      color: #20aea5;
      font-size: 15px;
      font-weight: bold;
      border-radius: 5px;
    }
  }
}
</style>
