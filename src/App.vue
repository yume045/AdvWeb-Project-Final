<template>
  <div id="app" class="mt-0">
    <nav class="navbar navbar-expand-xl navbar-dark bg-dark mb-5">
      <router-link to="/"><a class="navbar-brand" href="#">Web Project</a></router-link>
      <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarsExample06" aria-controls="navbarsExample06" aria-expanded="true" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="navbar-collapse collapse show" id="navbarsExample06" style="">
        <ul class="navbar-nav mr-auto">
          <li class="nav-item active">
            <router-link to="Dashboard"><a class="nav-link" href="#">Dashboard <span class="sr-only">(current)</span></a></router-link>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">ข่าวกีฬา</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">ข่าวบันเทิง</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">ข่าวการเมือง</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">ข่าวในพระราชสำนัก</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">ข่าวเกมส์</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">ข่าวต่างประเทศ</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">ข่าวไอที</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">อื่นๆ</a>
          </li>
        </ul>
        <form class="form-inline my-2 my-md-0 mr-4">
          <input class="form-control" type="text" placeholder="Search">
        </form>
        <button type="button" class="btn btn-outline-primary">Login Facebook</button>
      </div>
    </nav>
    <router-view/>
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style>
#app {
  font-family: 'Prompt', sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
nav {
  position: fixed;
}
</style>
