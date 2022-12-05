<script>
export default {
  name: "HeaderNav",
  data() {
    return {
      links: ["Home", "Pages", "Courses", "Features", "Blog", "Shop"],
    };
  },
};
</script>

<template>
  <nav class="main-nav">
    <ul class="d-flex justify-content-center">
      <li v-for="link in links">
        <a href="#">{{ link }}</a>
      </li>
    </ul>
  </nav>
</template>

<style lang="scss" scoped>
.main-nav {
  ul {
    list-style: none;
    margin-bottom: 0;
    padding-left: 0;
    a {
      display: inline-block;
      padding: 20px 10px;
      text-decoration: none;
      color: black;
      font-size: 16px;
    }
  }
}
</style>
