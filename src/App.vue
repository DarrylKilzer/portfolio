<template>
  <div id="app">
    <navbar></navbar>
    <h1>Darryl Kilzer Jr.</h1>
    <h3>Software Engineer</h3>
    <router-view></router-view>
  </div>
</template>

<script>
import Navbar from '@/components/Navbar'
export default {
  name: 'app',
  components: {
    Navbar
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  margin-top: 60px;
}

body {
  background-image: linear-gradient(rgba(0, 0, 0, .7), black), url(https://t2.ftcdn.net/jpg/00/05/05/01/400_F_5050151_1F8sdPz85J4SYmPdM4af6kZlzrHrNGcF.jpg);
  background-attachment: fixed;
}

.background {
  border-radius: 50px;
  border: none;
  background-color: rgba(0, 0, 0, .6);
  margin-top: 1%;
}

.description {
  border-radius: 50px;
  border: none;
  background-color: rgba(0, 0, 0, .6);
  padding: 7px;
  margin-top: 3%;
}

h1,
h2,
h3 {
  font-weight: normal;
  color: gray;
  text-shadow: 3px 3px 3px black;
}

ul {
  list-style-type: none;
  padding: 0;
}

li {
  display: inline-block;
  margin: 0 10px;
}

a {
  color: gray;
}
</style>
