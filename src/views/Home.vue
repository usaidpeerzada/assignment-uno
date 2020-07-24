<template>
  <div class="home">
    <NavBar />
    <Intro />
    <List />
  </div>
</template>

<script>
// @ is an alias to /src

import Intro from "@/components/Intro.vue";
import List from "@/components/List.vue";
import NavBar from "@/components/NavBar.vue";
export default {
  name: "Home",
  components: {
    Intro,
    List,
    NavBar
  }
};
</script>
<style scoped>
.home {
  display: inline-block;
}
</style>
