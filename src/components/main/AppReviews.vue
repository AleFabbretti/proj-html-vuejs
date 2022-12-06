<script>
export default {
  name: "AppReviews",
};
</script>

<template>
  <section class="culture">
    <div class="container d-flex justify-content-center">
      <div class="col-left">
        <h6>TESTIMONIALS</h6>
        <h2 class="mb-3">
          Why do people <br />
          <span>*Hearts*</span> Us?
        </h2>
        <p class="mb-4">
          Seeking for verbals of our service quality? Find them here. Everything
          is transparent and straight forward for your sense of justification.
        </p>
        <span
          ><a href="#" class="mx-2"
            >View all <i class="fa-solid fa-arrow-right"></i></a
        ></span>
      </div>
      <div class="col-right pt-5 position-relative">
        <div class="testimonials">
          <p>
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Fugiat
            natus quia alias quis deserunt tempora unde est amet sequi quidem et
            vitae molestias ipsa laboriosam, labore vero perspiciatis sed sit.
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Cupiditate
            laboriosam praesentium assumenda. Corrupti ab maxime quidem earum
            incidunt voluptatibus, deserunt ducimus illum? Quasi minima quos est
            optio magnam tempore reprehenderit.
          </p>
          <img src="../../assets/testimonial-avata-02.jpg" alt="avatar02" />
        </div>
      </div>
    </div>
  </section>
</template>

<style lang="scss" scoped>
.culture {
  margin-top: 80px;
}

.col-left {
  width: 30%;
  padding-bottom: 90px;
  padding-top: 180px;
  & h6 {
    color: grey;
    margin-bottom: 25px;
    & span {
      font-weight: bold;
    }
  }
  & h2 {
    font-weight: bold;
    font-size: 35px;
    & span {
      font-weight: 10;
      font-weight: bold;
      color: #20ad96;
    }
  }
  & span a {
    color: black;
    text-decoration: none;
    border-bottom: 1px solid lightgrey;
  }
}

.col-right {
  width: 40%;
  padding-bottom: 90px;
  margin-left: 120px;
  position: relative;
  & img {
    border-radius: 5px;
    position: absolute;
    z-index: 1;
  }
  & .about-us {
    position: absolute;
    top: 0;
    right: 0;
    z-index: 1;
    border-radius: 10px;
  }
  & .shape-02 {
    position: absolute;
    bottom: 0;
    right: 120px;
    z-index: 2;
  }
  & .shape-03 {
    position: absolute;
    top: 5px;
    right: 100px;
    z-index: 0;
  }
  & .testimonials {
    height: 350px;
    & img {
      width: 50px;
      border-radius: 50%;
      position: absolute;
      bottom: 0;
    }
  }
}
</style>
