<script>
export default {
  name: "TransformSection",
};
</script>

<template>
  <div class="d-flex container justify-content-center position-relative">
    <img
      class="shape01 position-absolute"
      src="../../assets/maxcoach-shape-01.png"
      alt="shape01"
    />
    <div class="col-left d-flex justify-content-end position-relative">
      <svg
        class="svg position-absolute"
        xmlns="http://www.w3.org/2000/svg"
        width="200"
        height="202"
      >
        <path
          class="elementor-shape-fill"
          d="M139.374 198.088c16.328 8.906 51.35-1.087 58.304-39.038 7.15-39.022-13.182-40.052-9.633-54.248 14.243-21.15 16.782-48.14 2.028-64.387-36.503-38.024-45.629 7.604-76.048-20.28C101.727 7.837 83.1-6.735 56.23 3.405 18.239 17.74 27.33 47.659 27.33 69.313c0 7.624-24.216 21.957-26.87 41.573-3.346 24.734 12.168 57.29 26.87 68.443 23.322 26.363 59.318 20.28 75.541 11.154 13.931-7.836 25.35 1.52 36.503 7.605z"
        />
      </svg>
      <img
        class="svg05 position-absolute"
        src="../../assets/maxcoach-shape-05.png"
        alt="shape05"
      />
      <img
        class="shape07 position-absolute"
        src="../../assets/maxcoach-shape-07.png"
        alt="shape07"
      />
      <img class="team" src="../../assets/home-3-team-image.png" alt="team" />
    </div>
    <div class="col-right pt-3">
      <h6 class="pb-3">EVERYTHING IN MAX COACH</h6>
      <h1 class="pb-2">We're here to <span>Transform</span> you!</h1>
      <p class="pb-2">
        As learners, people can enjoy great companionship from Maxcoach mentors
        and educators. We can help you develop and grow at your best.
      </p>
      <button>Get Free Guide</button>
    </div>
  </div>
</template>

<style lang="scss" scoped>
.shape01 {
  bottom: 0;
  left: -10px;
  scale: 70%;
}
.col-left {
  & .team {
    width: 80%;
    z-index: 1;
  }
  & .svg {
    left: 40px;
    top: 20px;
    scale: 70%;
    fill: #20ad96;
    opacity: 0.4;
  }
  & .svg05 {
    top: 100px;
    left: 0;
    scale: 80%;
  }
  & .shape07 {
    scale: 70%;
    top: 300px;
    right: 110px;
  }
}
.col-right {
  width: 30%;
  margin-left: 120px;
  margin-top: 50px;
  & h1 {
    font-weight: bold;
    & span {
      font-weight: 100;
      color: #20ad96;
    }
  }
  & span a {
    color: black;
    text-decoration: none;
    font-weight: bold;
    border-bottom: 1px solid lightgrey;
  }
}
button {
  border-radius: 5px;
  padding: 12px 50px;
  border: none;
  color: white;
  font-size: 14px;
  font-weight: bold;
  background-color: #20ad96;
}
</style>
