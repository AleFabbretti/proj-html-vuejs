<script>
import HeroMainTop from "./HeroMainTop.vue";
import CultureSection from "./CultureSection.vue";
import SkillSection from "./SkillSection.vue";
import CoursesSection from "./CoursesSection.vue";
import AppReviews from "./AppReviews.vue";
import TransformSection from "./TransformSection.vue";
import BlogSection from "./BlogSection.vue";
import NewsLetter from "./NewsLetter.vue";
export default {
  name: "AppMain",
  components: {
    HeroMainTop,
    CultureSection,
    SkillSection,
    CoursesSection,
    AppReviews,
    TransformSection,
    BlogSection,
    NewsLetter,
  },
};
</script>

<template>
  <HeroMainTop />
  <section class="gradient">
    <CultureSection />
    <SkillSection />
    <CoursesSection />
    <svg
      class="final"
      xmlns="http://www.w3.org/2000/svg"
      viewBox="0 0 100 100"
      preserveAspectRatio="none"
      height="100"
    >
      <path class="elementor-shape-fill" d="M0 0v100h100V0Q50 200 0 0" />
    </svg>
  </section>
  <AppReviews />
  <TransformSection />
  <BlogSection />
  <NewsLetter />
</template>

<style lang="scss" scoped>
.gradient {
  background: linear-gradient(white, #f6f6f6);
  & .final {
    fill: white;
    width: 100%;
  }
}
</style>
