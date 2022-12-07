<script>
import MainFooter from "./MainFooter.vue";
export default {
  name: "AppFooter",
  components: {
    MainFooter,
  },
};
</script>

<template>
  <footer>
    <div class="mycontainer d-flex justify-content-between">
      <MainFooter />
    </div>
    <div>
      <span class="copyright d-flex justify-content-center"
        ><i class="fa-regular fa-copyright"></i> 2020 MaxCoach. All Rights
        Reserved</span
      >
      <a href="#top" id="moving-top">
        <i class="fa-solid fa-arrow-up"></i>
      </a>
    </div>
  </footer>
</template>

<style lang="scss" scoped>
footer {
  background-color: #171621;
  margin-top: 80px;
  & .mycontainer {
    width: 900px;
    margin: auto;
  }
  & .copyright {
    color: #abab95;
    font-size: 10px;
  }
}
</style>
