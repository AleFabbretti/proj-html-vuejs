<script>
import HeroMainTop from "./HeroMainTop.vue";
import CultureSection from "./CultureSection.vue";
export default {
  name: "AppMain",
  components: {
    HeroMainTop,
    CultureSection,
  },
};
</script>

<template>
  <HeroMainTop />
  <CultureSection />
</template>

<style lang="scss" scoped></style>
