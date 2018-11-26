<template>
  <div id="app">
		<div> 
			<ShowBox />
		</div>
		<div class="tree">
			<Tree /> 
		</div>
  </div>
</template>

<script>
import ShowBox from './components/showbox/index.vue';
import Tree from './components/tree/index.vue';

export default {
  name: 'app',
  components: {
		ShowBox,
		Tree
  }
}
</script>

<style>
	#app {
		font-family: 'Avenir', Helvetica, Arial, sans-serif;
		-webkit-font-smoothing: antialiased;
		-moz-osx-font-smoothing: grayscale;
		text-align: center;
		color: #2c3e50;
		margin-top: 60px;
	}
	.tree {
		margin-top: 10px;
	}
</style>
