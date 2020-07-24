<template>
  <div class="intro">
    <div class="left-side"></div>
    <div class="main">
      <div class="top2">
        <input class="search" type="text" placeholder="Search" />
      </div>
      <div class="row">
        <div class="column">
          <div class="card">
            <h2>Hi John Doe.</h2>
            <p>
              Welcome back to this shit place ass clowns hey there. you are an
              ass and you suck boooo !
            </p>
            <img src="https://picsum.photos/200" alt="img" />
            <button class="button">View Details</button>
          </div>
        </div>
      </div>
      <h4 style="display: inline-block,; padding-left:22vw">Trending Blogs</h4>
      <div class="mid row">
        <!-- Props Component -->
        <InfoCard
          class="card"
          heading="Prototyping"
          para="lorem ipsum lorem ipsum lorem
       "
        />
        <InfoCard
          class="card"
          heading="Prototyping"
          para="lorem ipsum lorem ipsum lorem
          "
        />
        <InfoCard
          class="card"
          heading="Typography"
          para="lorem ipsum lorem ipsum lorem
       "
        />
      </div>
    </div>
    <div class="right-side"></div>
  </div>
</template>

<script>
import InfoCard from "./InfoCard";
export default {
  components: {
    InfoCard
  }
};
</script>

<style scoped>
.top2 {
  display: inline-block;
  margin: 0 65vh;
}
.right-side {
  grid-column: 3/4;
  background: grey;
}
.top1 {
  background: rgb(206, 206, 206);
  border-radius: 10px;
}
.img {
  float: right;
  padding-bottom: 30px;
}
.search {
  padding: 15px 84px;
  background: rgb(230, 228, 228);
  border: none;
  border-radius: 10px;
  margin: 10px;
}
.button {
  padding: 10px 20px;
  border: none;
  background: black;
  color: white;
  border-radius: 8px;
}
* {
  box-sizing: border-box;
}
.mid {
  display: flex;
  justify-content: center;
  margin: 40px 80px;
}
.card {
  margin-left: 20px;
}
</style>
