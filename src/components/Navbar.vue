<template>
  <div class="navbar">
    <div class="navbar-wrapper">
      <div class="container">
        <nav class="navbar navbar-inverse navbar-static-top">
          <div class="container">
            <div class="navbar-header">
              <button type="button" class="navbar-toggle collapsed" data-toggle="collapse" data-target="#navbar" aria-expanded="false" aria-controls="navbar">
                <span class="sr-only">Toggle navigation</span>
                <span class="icon-bar"></span>
                <span class="icon-bar"></span>
                <span class="icon-bar"></span>
              </button>
              <a class="navbar-brand" href="/">Darryl Kilzer Jr.</a>
            </div>
            <div id="navbar" class="navbar-collapse collapse" style="font-size:20px;">
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
  </div>
</template>


<script>
export default {
  name: 'navbar',
  data() {
    return {
      
    }
  },
  computed: {},
  methods: {},
  components: {}
}
</script>


<style scoped>

</style>