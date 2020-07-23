<template>
  <div class="intro">
    <div class="left-side"></div>
    <div class="main">
      <div class="top2">
        <input class="search" type="text" placeholder="Search" />
      </div>
      <div class="top1">
        <h2>Hi John Doe.</h2>
        <p>
          Welcome back to this shit place ass clowns hey there. you are an ass
          and you suck boooo !
        </p>
        <div class="img">
          <img src="https://picsum.photos/200" alt="img" />
        </div>

        <button class="button">View Details</button>
      </div>

      <div class="mid">
        <h3>Trending Blogs</h3>
        <div class="row">
          <div class="column">
            <div class="card">
              <h4>Prototyping</h4>
              <p>
                lorem ipsum dolor sit atem bull puss isem kissem lissem cheerem
                tissem.
              </p>
            </div>
          </div>
          <div class="column" style="color:white">
            <div class="card" style="background: black">
              <h4>Typography</h4>
              <p>
                lorem ipsum dolor sit atem bull puss isem kissem lissem cheerem
                tissem.
              </p>
            </div>
          </div>
          <div class="column">
            <div class="card">
              <h4>Color Palatte</h4>
              <p>
                lorem ipsum dolor sit atem bull puss isem kissem lissem cheerem
                tissem.
              </p>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="right-side"></div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.intro {
  display: grid;
  grid-template: auto 1fr auto / auto 1fr auto;
}
.main {
  grid-column: 2/3;
}
.left-side {
  grid-column: 1/3;
}
.right-side {
  grid-column: 3/4;
  background: grey;
}
.top1 {
  background: rgb(206, 206, 206);
  border-radius: 10px;
  display: inline-block;
  margin: 10px;
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

body {
  font-family: Arial, Helvetica, sans-serif;
}

/* Float four columns side by side */
.column {
  flex-direction: column;
  width: 25%;
  padding: 0 10px;
}

/* Remove extra left and right margins, due to padding in columns */
.row {
  display: flex;
  justify-content: center;
}

/* Clear floats after the columns */
.row:after {
  content: "";
  display: table;
  clear: both;
}

/* Style the counter cards */
.card {
  box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2); /* this adds the "card" effect */
  padding: 16px;
  text-align: center;
  background-color: #f1f1f1;
  border-radius: 30px;
}

/* Responsive columns - one column layout (vertical) on small screens */
@media screen and (max-width: 600px) {
  .column {
    width: 100%;
    display: block;
    margin-bottom: 20px;
  }
}
</style>
