<template>
    <nav class="navbar navbar-expand-lg bg-primary">
      <div class="container justify-content-around">
          <div class="navbar-nav">
              <router-link to="/" class="nav-link active" aria-current="page" ><span class="material-icons-round">
                home
                </span></router-link>
              <router-link to="/about" class="nav-link" ><span class="material-icons-round">
                info
                </span></router-link>
              <router-link to="/posts" class="nav-link" ><span class="material-icons-round">
                featured_play_list
                </span></router-link>
          </div>
      </div>
      </nav>
</template>

<script>
export default {
  name:"NavComp"
}
</script>
<style scoped>
  .material-icons-round{
    color: yellow;
    font-size: 1.4em;
    background-color: rgba(128, 128, 128, 0.219) ;
    padding: 0.3em;
    border-radius: 50%;
    margin: 0.1em;
  }
  
  
</style>