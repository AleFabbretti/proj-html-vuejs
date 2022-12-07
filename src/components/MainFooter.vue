<script>
export default {
  name: "MainFooter",
  data() {
    return {
      exploreMenu: [
        {
          label: "Start here",
          href: "#",
        },
        {
          label: "Blog",
          href: "#",
        },
        {
          label: "About us",
          href: "#",
        },
        {
          label: "Success story",
          href: "#",
        },
        {
          label: "Courses",
          href: "#",
        },
        {
          label: "Contact us",
          href: "#",
        },
      ],
      informationMenu: [
        {
          label: "Membership",
          href: "#",
        },
        {
          label: "Purchase guide",
          href: "#",
        },
        {
          label: "Privacy policy",
          href: "#",
        },
        {
          label: "Terms of services",
          href: "#",
        },
      ],
    };
  },
};
</script>

<template>
  <div class="main-footer container py-5 px-0">
    <div class="agency">
      <div class="address">
        <h5 class="mb-3">Address</h5>
        <small class="street">382 NE 191st # 87394 Miami, FL 33179-3899</small>
        <small class="number"
          >+1 (305) 547-9909 (9am - 5pm EST, Monday - Friday)</small
        >
        <small class="email">support@maxcoach.com</small>
      </div>
      <div class="social mt-4">
        <a href="#">
          <i class="fa-brands fa-square-facebook"></i>
        </a>
        <a href="#">
          <i class="fa-brands fa-twitter"></i>
        </a>
        <a href="#">
          <i class="fa-brands fa-instagram"></i>
        </a>
        <a href="#">
          <i class="fa-brands fa-linkedin"></i>
        </a>
      </div>
    </div>
    <nav class="menu-links">
      <ul class="">
        <h5 class="mb-3">Explore</h5>
        <li class="mb-2" v-for="link in exploreMenu">
          <a :href="link.href">{{ link.label }}</a>
        </li>
      </ul>
    </nav>
    <nav class="menu-links">
      <ul class="">
        <h5 class="mb-3">Information</h5>
        <li class="mb-2" v-for="link in informationMenu">
          <a :href="link.href">{{ link.label }}</a>
        </li>
      </ul>
    </nav>
  </div>
</template>

<style lang="scss" scoped>
.main-footer {
  display: flex;
  justify-content: space-between;
  color: #696969;
  & h5 {
    font-size: 15px;
    font-weight: bolder;
    color: white;
  }
  & .address small {
    display: block;
    margin-bottom: 5px;
  }
  & .social a {
    color: #b4b4b4;
    margin-right: 30px;
    &:hover {
      color: white;
    }
    & i {
      font-size: 25px;
    }
  }
  & .menu-links {
    display: flex;
    & ul {
      list-style: none;
      & li a {
        color: #696969;
        text-decoration: none;
      }
    }
  }
}
</style>
