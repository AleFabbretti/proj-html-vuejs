<script>
export default {
  name: "CardCourses",
  props: {
    info: Object,
  },
};
</script>

<template>
  <div class="card">
    <img :src="`/src/assets/${info.Image}`" alt="" />
    <div class="description">
      <h4 class="mt-3">{{ info.price }}</h4>
      <p>{{ info.description }}</p>
      <div class="details d-flex justify-content-start">
        <span>{{ info.lessons }}</span>
        <span class="mx-5"
          ><i class="fa-solid fa-user mx-2"></i>{{ info.students }}</span
        >
      </div>
    </div>
  </div>
</template>

<style lang="scss" scoped>
.card {
  width: calc(100% / 3 - 20px);
  border: none;
  & img {
    max-width: 100%;
    max-height: 100%;
    border-radius: 5px;
  }
  & .description {
    margin-left: 20px;
    width: 70%;
    text-align: start;
    & h4 {
      font-weight: bolder;
      color: #20ad96;
    }
    & p {
      font-weight: bolder;
    }
    & .details span {
      color: grey;
      font-size: small;
    }
  }
}
</style>
