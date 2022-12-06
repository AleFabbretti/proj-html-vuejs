<script>
import HeroMainTop from "./HeroMainTop.vue";
import CultureSection from "./CultureSection.vue";
import SkillSection from "./SkillSection.vue";
export default {
  name: "AppMain",
  components: {
    HeroMainTop,
    CultureSection,
    SkillSection,
  },
};
</script>

<template>
  <HeroMainTop />
  <CultureSection />
  <SkillSection />
</template>

<style lang="scss" scoped></style>
