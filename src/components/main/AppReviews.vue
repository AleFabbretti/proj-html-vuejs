<script>
export default {
  name: "AppReviews",
};
</script>

<template>
  <section class="culture">
    <div class="container d-flex justify-content-between">
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
        <div class="testimonials fade">
          <p>
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Fugiat
            natus quia alias quis deserunt tempora unde est amet sequi quidem et
            vitae molestias ipsa laboriosam, labore vero perspiciatis sed sit.
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Cupiditate
            laboriosam praesentium assumenda. Corrupti ab maxime quidem earum
            incidunt voluptatibus, deserunt ducimus illum? Quasi minima quos est
            optio magnam tempore reprehenderit. Lorem ipsum dolor sit amet
            consectetur adipisicing elit. Fugiat natus quia alias quis deserunt
            tempora unde est amet sequi quidem et vitae molestias ipsa
            laboriosam, labore vero perspiciatis sed sit. Lorem ipsum dolor sit
            amet consectetur adipisicing elit. Cupiditate laboriosam praesentium
            assumenda. Corrupti ab maxime quidem earum incidunt voluptatibus,
            deserunt ducimus illum? Quasi minima quos est optio magnam tempore
            reprehenderit. Lorem ipsum dolor sit amet consectetur adipisicing
            elit. Fugiat natus quia alias quis deserunt tempora unde est amet
            sequi quidem et vitae molestias ipsa laboriosam, labore vero
            perspiciatis sed sit. Lorem ipsum dolor sit amet consectetur
            adipisicing elit. Cupiditate laboriosam praesentium assumenda.
            Corrupti ab maxime quidem earum incidunt voluptatibus, deserunt
            ducimus illum? Quasi minima quos est optio magnam tempore
            reprehenderit.
          </p>
          <img src="../../assets/testimonial-avata-02.jpg" alt="avatar02" />
        </div>
        <div class="testimonials upper">
          <h5 class="pb-4">
            Professional team specialists and passionate mentors at reach
          </h5>
          <p>
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Fugiat
            natus quia alias quis deserunt tempora unde est amet sequi quidem et
            vitae molestias ipsa laboriosam, labore vero perspiciatis sed sit.
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Cupiditate
            laboriosam praesentium assumenda. Corrupti ab maxime quidem earum
            incidunt voluptatibus, deserunt ducimus illum?
          </p>
          <div class="d-flex pt-3">
            <img src="../../assets/testimonial-avata-01.jpg" alt="avatar01" />
            <div class="mx-3">
              <p class="fw-bold">MADLEY PONDOR</p>
              <span class="small">/IT specialist</span>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<style lang="scss" scoped>
.culture {
  margin-top: 10px;
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
    font-weight: bold;
    text-decoration: none;
    border-bottom: 1px solid lightgrey;
  }
}

.col-right {
  width: 40%;
  padding-bottom: 90px;
  margin-left: 120px;
  position: relative;
  & .testimonials {
    background-color: white;
    box-shadow: 5px 5px 35px rgba($color: #000000, $alpha: 0.15);
    padding: 20px;
    border-radius: 20px;
    & img {
      width: 60px;
      border-radius: 50%;
    }
    & h5 {
      font-weight: bold;
    }
  }
  .fade {
    opacity: 0.2;
  }
  .upper {
    width: 120%;
    position: absolute;
    z-index: 1;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
  }
}
</style>
