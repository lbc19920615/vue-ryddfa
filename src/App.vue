<template>
	<div id="app">
		<EchartDemo></EchartDemo>
	</div>
</template>

<script>
	import EchartDemo from './components/EchartsDemo/index'

export default {
  name: 'App',
  components: {
    EchartDemo,
  }
}
</script>

<style>
	#app {
		font-family: Avenir, Helvetica, Arial, sans-serif;
		-webkit-font-smoothing: antialiased;
		-moz-osx-font-smoothing: grayscale;
		text-align: center;
		color: #2c3e50;
		margin-top: 60px;
	}
</style>