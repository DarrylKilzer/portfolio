<template>
  <ul class="nav justify-content-center">
    <li class="nav-item">
      <a class="nav-link active" href="#">DK</a>
    </li>
    <li class="nav-item">
      <a class="nav-link" href="https://darrylkilzer.github.io/resume/">Resumé</a>
    </li>
    <li class="nav-item">
      <button id="viewabout" type="button" class="btn btn-outline-info" @click="go('/about')">About</button>
    </li>
    <li class="nav-item">
      <a class="nav-link disabled" href="#">Disabled</a>
    </li>
  </ul>
  <!-- <div class="navbar">
    <div class="navbar-wrapper">
      <div class="container">
        <nav class="navbar navbar-inverse navbar-static-top">
          <div class="container">
            <div class="navbar-header">
              <button type="button" class="navbar-toggle" data-toggle="collapse" data-target="#navbar" aria-expanded="true" aria-controls="navbar">
                
                <span class="sr-only">Toggle navigation</span>
                <span class="icon-bar"></span>
                <span class="icon-bar"></span>
                <span class="icon-bar"></span>
              </button>
              <router-link to="/" class="navbar-brand">Darryl Kilzer Jr.</router-link>
            </div>
            <div id="navbar" class="navbar-collapse" style="font-size:20px;">
              <ul class="nav navbar-nav">
                <li>
                  <a href="https://darrylkilzer.github.io/resume/">Resumé</a>
                </li>
                <li>
                  <router-link to="about">About</router-link>
                </li>
                <li>
                  <router-link to="projects">Projects</router-link>
                </li>
                <li>
                  <a class="fa fa-github" href="https://github.com/DarrylKilzer"> /darrylkilzer</a>
                </li>
              </ul>
            </div>
          </div>
        </nav>
      </div>
    </div>
  </div> -->
</template>


<script>
  export default {
    name: 'navbar',
    data() {
      return {

      }
    },
    computed: {},
    methods: {
      go(path){
        this.$router.push(path)
      }
    },
    components: {}
  }
</script>


<style scoped>
  .navbar {
    padding: .4rem
  }

  a {
    color: inherit;
  }

  a:visited {
    color: inherit;
  }

  a:focus {
    color: aqua;
  }
</style>