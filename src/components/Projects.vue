<template>
  <div class="projects">
    <div class="row">
      <div class="col-xs-3 col-xs-offset-3">
        <img class="image-effects" src="../../images/dmapp1.png" alt="image">
        <div class="description">
          <h3>An application created for "Dungeons and Dragons" Dungeon Masters. This app is a tool to allow for a more smooth transition through the encounter phase of game play.
          </h3>
          <a href="https://dmem.herokuapp.com/">
            <i class="fa fa-external-link-square spacing"></i> See it!</a>
          <a href="https://github.com/DarrylKilzer/DMapp">
            <i class="fa fa-github"></i> Code</a>
        </div>
      </div>
    </div>
  </div>
</template>

<script>

export default {
  name: 'projects',
  data() {
    return {
    }
  },
  components: {}
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.image-effects{
  height: 250px;
}
.image-effects:hover {
  content: url("../../images/dmapp2.png");
}
.spacing{
  word-spacing: 10px;
}
</style>