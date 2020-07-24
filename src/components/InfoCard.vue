<template>
  <div class="any">
    <div :class="row">
      <div :class="column">
        <div :class="card">
          <h4>{{ heading }}</h4>
          <p>
            {{ para }}
          </p>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  props: ["heading", "para"]
};
</script>

<style>
body {
  font-family: Arial, Helvetica, sans-serif;
}
.column {
  display: flex;
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
