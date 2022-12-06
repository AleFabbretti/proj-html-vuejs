<script>
export default {
  name: "SkillSection",
};
</script>

<template>
  <section class="skills">
    <div class="container d-flex justify-content-center position-relative">
      <img
        class="position-absolute bottom-0 end-60"
        src="../../assets/maxcoach-shape-07.png"
        alt="shape07"
      />
      <div class="col-left pt-5">
        <img
          class="stock"
          src="../../assets/stock-full-hd-11-670x450.jpg"
          alt="stock-full"
        />
        <img
          class="shape position-absolute"
          src="../../assets/maxcoach-shape-05.png"
          alt="shape05"
        />
        <img
          class="svg position-absolute top-0 start-0"
          src="../../assets/svg-0.svg"
          alt="svg0"
        />
        <img
          class="youtube"
          src="../../assets/icon-youtube-play.png"
          alt="youtube"
        />
      </div>
      <div class="col-right pt-5">
        <h6>HOW WE WORK</h6>
        <h1>Upgrade Your Skills <span>Upgrade Your Life</span></h1>
        <p>
          Opening up more opportunities in front of you to get the ticket to
          more enjoyable door in life. Getting equipped with new skills for new
          sets of insights into your career. Max coach accompany learnes in
          every stage of learning.
        </p>
        <span
          ><a href="#" class="mx-2"
            >Download free Guidebook <i class="fa-solid fa-arrow-right"></i></a
        ></span>
      </div>
    </div>
  </section>
</template>

<style lang="scss" scoped>
.skills {
  margin-top: 70px;
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

.col-left {
  padding-bottom: 90px;
  position: relative;
  flex-grow: 1;
  display: flex;
  justify-content: flex-end;
  & .stock {
    width: 90%;
    border-radius: 5px;
    z-index: 2;
    padding-right: 80px;
  }
  & .youtube {
    position: absolute;
    top: 50%;
    left: 50%;
    margin: -40px 0 0 -25px;
    z-index: 3;
  }
  & .shape {
    top: 80px;
    left: 0;
    z-index: 1;
  }
}
</style>
