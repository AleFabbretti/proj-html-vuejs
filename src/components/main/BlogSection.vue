<script>
import CardCourses from "./CardCourses.vue";
export default {
  name: "BlogSection",
  components: {
    CardCourses,
  },
  data() {
    return {
      Lists: [
        {
          Image: "artist-blog-03-480x325.jpeg",
          description: "Brush Strokes Energize Trees in Paintings",
          lessons: "May 15, 2020",
          students: "688 views",
        },
        {
          Image: "artist-blog-02-480x325.jpg",
          description: "Poket-Sized Notebooks Hold Miniature Painting.",
          lessons: "May 15, 2020",
          students: "603 views",
        },
        {
          Image: "artist-blog-01-480x325.jpg",
          description: "Connection Between Self-Portraits and Identity.",
          lessons: "May 15, 2020",
          students: "397 views",
        },
      ],
    };
  },
};
</script>

<template>
  <section>
    <div class="container text-center">
      <h6 class="pb-4">READ FOR MORE JOYMENT</h6>
      <h1>Latest from <span class="style">Our Blogs</span></h1>
      <div class="cards">
        <CardCourses v-for="List in Lists" :info="List" />
      </div>
    </div>
  </section>
</template>

<style lang="scss" scoped>
section {
  background-color: #f8f8f8;
  padding-bottom: 80px;
  margin-top: 70px;
}
.container {
  padding-top: 100px;
}
.style {
  color: #20ad96;
  font-weight: bold;
}
.cards {
  display: flex;
  justify-content: space-between;
  padding-top: 60px;
}
</style>
