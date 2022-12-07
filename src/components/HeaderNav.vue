<script>
export default {
  name: "HeaderNav",
  data() {
    return {
      menu: [
        {
          label: "Home",
          link: "/",
        },
        {
          label: "Pages",
          link: "/pages",
        },
        {
          label: "Courses",
          link: "/courses",
        },
        {
          label: "Features",
          link: "/features",
        },
        {
          label: "Blog",
          link: "/blog",
        },
        {
          label: "Shop",
          link: "/shop",
        },
      ],
    };
  },
};
</script>

<template>
  <nav class="main-nav">
    <ul class="d-flex justify-content-center">
      <li v-for="item in menu">
        <a href="{{ item.link }}">{{ item.label }}</a>
        <i class="fa-solid fa-chevron-down"></i>
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
      color: #3f3a64;
      font-size: 16px;
    }
    a:hover {
      transform: scale(1.1);
    }
  }
  i {
    font-size: 8px;
    align-self: center;
  }
}
</style>
