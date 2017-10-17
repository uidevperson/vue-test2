<template>
	<div>
		<h1>this count is test {{count}}</h1>
		<button @click='count+=10'>increment</button>
	</div>
</template>

<script type="text/javascript">
	export default {
		data(){
			return {
				count: 0
			};
		}
	}
</script>