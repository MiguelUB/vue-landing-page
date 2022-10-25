<template>
  <label id = "container_home" class="col-lg-12 row">
    <div id = "info_home" class = "col-lg-5">
      <h1>HELLO</h1>
      <h2>dribble</h2>
      <p>sjsjwjqj jrqjrqjqwjr jrejqtew jtejtje ejjwjte wetjwjt  twjtwj jtw jewj wjwj j j</p>
      <button id="launch_btn" type="button" >GO LUNCH</button>
    </div>
    <div  class = "col-lg-7">
      <img src="../assets/img_1.png">
    </div>

  </label>
</template>

<script>
export default {
  name: "container_Hello"
}
</script>

<style scoped>
#info_home{
  text-align: left;
  padding-right: 20px;
}

#container_home{
  margin-top: 100px;
}

#launch_btn{
  background-color: darkorchid;
  border-radius: 20px;
  padding-top: 10px;
  padding-bottom: 10px;
  padding-left: 25px;
  padding-right: 25px;
}
</style>