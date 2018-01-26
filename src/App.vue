<template>
  <div id="app" class="font">
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
}
body {
		margin:0;
		padding:0;
		text-align:center;
	}
  .pad-top{
    padding-top: 1rem;
  }
	.content-block {
		position:relative;
		width:100%;
		height:100vh;
		overflow:hidden;
	}
	.text {
		font:2rem / 2rem sans-serif;
		width:200px;
		position:absolute;
		top:85px;
		left:80%;
		margin-left:-50px;
		color:#fff;
		text-shadow:0 0 10px #000;
    text-align:center;
	}
	.full {
		height: 50vh;
	}
	.hide{
		display: none;
	}
	.bg {
		z-index:-1; /* put it below the text */
		position:absolute;
		top:0;
		bottom:0;
		left:0;
		right:0;
		background:url('./assets/home/ground_3.png') 0 0, url('./assets/home/ground_2.png') 40% 0, url('./assets/home/ground_1.png') 70% 0, url('./assets/home/clouds_1.png') 80% 0, url('./assets/home/sky.png') 90%, 0;
		-webkit-transition: left 300s linear;
		   -moz-transition: left 300s linear;
		     -o-transition: left 300s linear;
		        transition: left 300s linear;
	}
	#viewabout{
		margin: 25px;
	}
	.font{
		color: aquamarine;
		text-shadow:0 0 60px #1B1;
		font-size: 1.8rem;
		
	}
	#bg-hover:hover, #bg-target:target {
		left:-9999px;
	}
	#bg-keyframes {
		-webkit-animation: moving-images 400s linear infinite;
		   -moz-animation: moving-images 400s linear infinite;
		     -o-animation: moving-images 400s linear infinite;
		        animation: moving-images 400s linear infinite;
	}
	@keyframes moving-images {
		0%   {left:0;}
		50%  {left:-9999px;}
		100% {left:0;}
	}
	@-moz-keyframes moving-images { 
		0%   {left:0;}
		50%  {left:-9999px;}
		100% {left:0;}
	}
	@-webkit-keyframes moving-images { 
		0%   {left:0;}
		50%  {left:-9999px;}
		100% {left:0;}
	}
	@-o-keyframes moving-images { 
		0%   {left:0;}
		50%  {left:-9999px;}
		100% {left:0;}
	}

</style>
