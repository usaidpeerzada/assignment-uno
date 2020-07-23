<template>
  <div class="main">
    <h4 style="text-align:left; padding-left: 300px">List of Blogs</h4>
    <table>
      <thead>
        <tr>
          <th>Date</th>
          <th>Post Title</th>
          <th>Status</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td><strong>showSpeed</strong></td>
          <td>1jskadbcjadsbcljdsbacbyulyboubrqelccycabyuewblwq</td>
          <td>The speed of the show/reveal</td>
        </tr>
        <tr></tr>
      </tbody>
    </table>

    Resources
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
body {
  background: #c4c4c4;
  color: #444;
  font: 100%/30px "Helvetica Neue", helvetica, arial, sans-serif;
  text-shadow: 0 1px 0 #fff;
}

strong {
  font-weight: bold;
}

em {
  font-style: italic;
}

table {
  background: #f5f5f5;
  border-collapse: separate;
  box-shadow: inset 0 1px 0 #fff;
  font-size: 12px;
  line-height: 24px;
  margin: 30px auto;
  text-align: left;
  width: 800px;
}

th {
  background: rgb(219, 219, 219);
  border: none;
  border-radius: 2px;
  color: #000;
  font-weight: bold;
  padding: 10px 15px;
  position: relative;
}

th:after {
  content: "";
  display: block;
  height: 25%;
  left: 0;
  margin: 1px 0 0 0;
  position: absolute;
  top: 25%;
  width: 100%;
}

td {
  padding: 10px 15px;
  position: relative;
  transition: all 300ms;
}
</style>
