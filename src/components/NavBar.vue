<template>
  <div id="nav">
    <router-link to="/">
      <img class="icon-img" src="" alt="" />
    </router-link>
    <router-link to="/"
      ><img class="icon-img" src="" alt=""/><i class="fas fa-briefcase"></i
    ></router-link>
    <router-link to="/"
      ><img class="icon-img" src="" alt=""/><i class="fas fa-briefcase"></i
    ></router-link>
    <router-link to=""
      ><img class="icon-img" src="" alt=""/><i class="fa fas fa-briefcase"></i
    ></router-link>
    <router-link to=""
      ><img class="icon-img" src="" alt=""/><i class="fas fa-briefcase"></i
    ></router-link>
    <router-link to=""
      ><img class="icon-img set" src="" alt=""/><i class="fas fa-briefcase"></i
    ></router-link>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
body {
  padding: 0;
  margin: 0;
  background-color: white;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#nav {
  display: flex;
  flex-direction: column;
  position: sticky;
  background-color: #383135;
  width: 75px;
  margin: 20px 20px;
  border-radius: 23px;
}
.icon-img {
  width: 18px;
  height: 18px;
  margin: 20px 28px;
}
.icon-img.set {
  margin-top: 150px;
}
</style>
