<script>
export default {
  name: "CultureSection",
};
</script>

<template>
  <section class="culture">
    <div class="container d-flex justify-content-center">
      <div class="col-left pt-5">
        <h6>EVERYTHING IN <span>MAX COACH</span></h6>
        <h2 class="mb-3">
          Learn about our <span>Work Culture</span> at Max Coach
        </h2>
        <p class="mb-4">
          Spend some times to visit our website or head office and discover our
          current courses, enrollment procedure, and registration deadline.
          we're opening new classes every beginning of each mounth.
        </p>
        <span
          >Have questions?<a href="#" class="mx-2"
            >Get free guide <i class="fa-solid fa-arrow-right"></i></a
        ></span>
      </div>
      <div class="col-right pt-5">
        <img
          class="position-relative"
          src="../../assets/stock-full-hd-10-ohki1ayywq3cqutettrncduujpoaorifqu4relt2ts.jpg"
          alt="stock"
        />
        <img
          class="about-us"
          src="../../assets/about-us-01-ohkia3qg98rq9vg3s0mn2hkflr1migdqdw370qnegc.jpg"
          alt="about"
        />
        <img
          class="shape-02"
          src="../../assets/maxcoach-shape-02.png"
          alt="shape02"
        />
        <img
          class="shape-03"
          src="../../assets/maxcoach-shape-07.png"
          alt="shape07"
        />
      </div>
    </div>
  </section>
</template>

<style lang="scss" scoped>
.culture {
  margin-top: 80px;
}

.col-left {
  width: 25%;
  padding-bottom: 90px;
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
      color: #20ad96;
    }
  }
  & span a {
    color: #20ad96;
    text-decoration: none;
    border-bottom: 1px solid lightgrey;
  }
}

.col-right {
  width: 50%;
  padding-bottom: 90px;
  margin-left: 200px;
  position: relative;
  & img {
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
}
</style>
