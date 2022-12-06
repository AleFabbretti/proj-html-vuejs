<script>
import HeroMainTop from "./HeroMainTop.vue";
import CultureSection from "./CultureSection.vue";
import SkillSection from "./SkillSection.vue";
import CoursesSection from "./CoursesSection.vue";

export default {
  name: "AppMain",
  components: {
    HeroMainTop,
    CultureSection,
    SkillSection,
    CoursesSection,
  },
};
</script>

<template>
  <HeroMainTop />
  <CultureSection />
  <SkillSection />
  <CoursesSection />
</template>

<style lang="scss" scoped></style>
