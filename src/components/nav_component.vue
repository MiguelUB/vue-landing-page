<template>
  <div class="pos-f-t">
  <div class="collapse" id="navbarToggleExternalContent">
    <div class="bg-dark p-4">
      <h4 class="text-white">Collapsed content</h4>
      <span class="text-muted">Toggleable via the navbar brand.</span>
    </div>
  </div>
  <nav class="navbar navbar-expand-lg navbar-default">
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarText" aria-controls="navbarText" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id = "navbarText">
      <ul class="nav navbar-nav mx-auto">
        <li class="nav-item active">
          <a class="nav-link" href="#">Portfolio</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">About Me</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Contact</a>
        </li>
      </ul>
      <ul class="nav navbar-nav" style="margin-right: 15px">
        <form class="form-inline my-2 my-lg-0" >
          <input class="form-control mr-sm-2" type="search" placeholder="Search" aria-label="Search">
        </form>
      </ul>
    </div>
  </nav>
  </div>
</template>

<script>
export default {
  name: "nav_component"
}
</script>

<style scoped>
button{
  margin-left: 50px;
}
nav{
  background-color: rgba(255, 0, 0, 0);
}
ul{
  display: flex;
  flex-direction: row;
}
li{
  margin-right: 20px;
}

</style>