<script>
import CardCourses from "./CardCourses.vue";
export default {
  name: "CoursesSection",
  components: {
    CardCourses,
  },
  data() {
    return {
      Lists: [
        {
          Image: "course-02-480x298.jpg",
          price: "$40.00",
          description: "Learning to write as a professional Author.",
          lessons: "20 lessons",
          students: "50 students",
        },
        {
          Image: "stock-full-hd-03-480x298.jpg",
          price: "$0.00",
          description: "Customer-centric Info-tech Strategies.",
          lessons: "24 lessons",
          students: "769 students",
        },
        {
          Image: "stock-full-hd-04-480x298.jpg",
          price: "$19.00",
          description: "Open Programming Courses for Everyone: Python.",
          lessons: "17 lessons",
          students: "62 students",
        },
      ],
    };
  },
};
</script>

<template>
  <section class="container text-center pt-5">
    <h6 class="pb-4">JOIN MAX COACH AT BEST</h6>
    <h1>Latest online <span>Courses</span></h1>
    <div class="cards">
      <CardCourses v-for="List in Lists" :info="List" />
    </div>
    <div class="courses pt-5">
      <p>
        Control your personal preference settings to get notified about <br />
        appropriate courses.<a href="#" class="mx-2"
          >View all courses <i class="fa-solid fa-arrow-right"></i
        ></a>
      </p>
    </div>
  </section>
</template>

<style lang="scss" scoped>
.cards {
  display: flex;
  justify-content: space-between;
  padding-top: 60px;
}
.courses a {
  text-decoration: none;
  color: black;
  border-bottom: 1px solid lightgray;
  font-weight: bold;
}
</style>
