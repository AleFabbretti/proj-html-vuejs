<script>
export default {
  name: "NewsLetter",
};
</script>

<template>
  <section class="d-flex justify-content-center pt-5">
    <div class="text-center">
      <h1>Subscribe <span>Newsletter</span></h1>
      <p>
        Enter your email address to register to our news letter subscription
        <br />
        delivered on a regular basis!
      </p>
      <div>
        <form class="d-flex pt-5" @submit.prevent="subscribe">
          <input
            class="search"
            type="text"
            placeholder="Enter your email"
            name="mail"
          />
          <button class="px-4">subscribe</button>
        </form>
      </div>
    </div>
  </section>
</template>

<style lang="scss" scoped>
h1 span {
  color: #20ad96;
}
p {
  color: grey;
  font-weight: bold;
  padding-top: 20px;
}
.search {
  width: 100%;
  padding: 10px;
  border: none;
  border-radius: 4px;
  background-color: #f5f5f5;
  color: #000;
  font-size: 14px;
  flex-grow: 1;
}
button {
  background-color: #20ad96;
  color: white;
  border: none;
  font-weight: bold;
  border-radius: 0 5px 5px 0;
}

button:hover {
  background-color: white;
  color: #20ad96;
}
</style>
