<script>
export default {
  name: "SkillSection",
};
</script>

<template>
  <section class="skills">
    <div class="container d-flex justify-content-center">
      <div class="col-left pt-5">
        <img src="../../assets/stock-full-hd-11-670x450.jpg" alt="stock-full" />
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
  margin-top: 30px;
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
  width: 50%;
  padding-bottom: 90px;
  position: relative;
  & img {
    border-radius: 5px;
  }
}
</style>
