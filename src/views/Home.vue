<template>
  <div class="home">
    <HelloWorld />
    <Intro />
    <List />
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from "@/components/HelloWorld.vue";
import Intro from "@/components/Intro.vue";
import List from "@/components/List.vue";

export default {
  name: "Home",
  components: {
    HelloWorld,
    Intro,
    List
  }
};
</script>
<style scoped></style>
