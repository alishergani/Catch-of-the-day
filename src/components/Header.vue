<template>
	<div class="header">
		<h1>Catch 
		<span class="ofThe">
			<span class="of">of</span><span class="the">the</span>
		</span> 
		Day</h1>
	</div>
</template>


<style lang="scss" scoped>
	.header {
		font-family: "Open Sans", sans-serif;
		width: 100%;
		h1{
			width: 100%;
			font-size: 144px;
    	line-height: 1;
			font-family: 'blanchcaps_inline', sans-serif;
	    text-align: center;
	    font-weight: normal;
	    margin: 0;
	    display: flex;
			.ofThe {
				display: flex;
		    font-size: 3rem;
		    color: #f5a623;
		    -ms-flex-pack: center;
		    justify-content: center;
		    -ms-flex-align: center;
		    align-items: center;
		    background: url('../assets/images/anchor.svg') center no-repeat;
		    background-size: cover;
		    padding: 0 1rem;
		    .of {
		    	padding-right: 2rem;
				  position: relative;
				  right: -0.5rem;
		    }
			}
		}
	}
</style>