<template>
  <div id="app" >
    <nav_component></nav_component>
    <div class="container">
      <container_Hello></container_Hello>
    </div>
  </div>
</template>

<script>
import nav_component from "@/components/nav_component";
import container_Hello from "@/components/container_Hello";
export default {
  name: 'App',
  components: {
    container_Hello,
    nav_component
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  background-image: url("@/assets/bg_bggenerator_com.png");
  background-size: cover;
}
.container{

}
</style>
