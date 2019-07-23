<script>
	export let name;
</script>

<style>		
	.wrapper {
		display: grid;
		grid-template-columns: 1fr 1fr 1fr;
		grid-template-rows: 20% 80%;
		grid-column-gap: 0px;
		grid-row-gap: 0px;
	}

	.box {
		background-color: #444;
		color: #fff;		
		padding: 20px;
		font-size: 150%;
	}

	.header {
		background-color: #0000;
		grid-area: 1/4;					
		padding: 20px;
		font-size: 150%;
	}	 

	.content {
		grid-row: 2;
		grid-column:1/4;		
	}
</style>

<div class="wrapper">
	<div class="box header"></div>
	<div class="box content"></div>
</div>
