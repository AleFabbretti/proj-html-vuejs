<script>
import HeroMainTop from "./HeroMainTop.vue";
import CultureSection from "./CultureSection.vue";
import SkillSection from "./SkillSection.vue";
import CoursesSection from "./CoursesSection.vue";
import AppReviews from "./AppReviews.vue";
export default {
  name: "AppMain",
  components: {
    HeroMainTop,
    CultureSection,
    SkillSection,
    CoursesSection,
    AppReviews,
  },
};
</script>

<template>
  <HeroMainTop />
  <section class="gradient">
    <CultureSection />
    <SkillSection />
    <CoursesSection />
    <img class="final" src="../../assets/svg-1.svg" alt="svg1" />
  </section>
  <AppReviews />
</template>

<style lang="scss" scoped>
.gradient {
  background: linear-gradient(white, #f6f6f6);
  & .final {
  }
}
</style>
