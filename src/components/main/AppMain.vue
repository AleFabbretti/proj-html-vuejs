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
  <CultureSection />
  <SkillSection />
  <CoursesSection />
  <AppReviews />
</template>

<style lang="scss" scoped></style>
