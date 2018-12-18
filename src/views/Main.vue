<template>
	<div class="page main">
		<FishList />
		<Order />
		<Inventory />
	</div>
</template>

<script>
import FishList from './../components/FishList.vue'
import Order from './../components/Order.vue'
import Inventory from './../components/Inventory.vue'
export default {
	components: {
		FishList,
		Order,
		Inventory
	}
}
</script>

<style lang="scss">
	.main {
		max-width: 1500px;
    margin: 0 auto;
    margin-top: 5vh;
		height: 90vh;
		display: flex;
		&__part {
	    flex: 1 4 auto;
	    padding: 20px;
	    border: 10px double #1a1a1a;
	    position: relative;
	    background: #fff;
	    transition: all 0.3s;
	    box-shadow: 0 5px 5px rgba(0,0,0,0.1);
	    overflow: auto;
	    &.order {
	    	border-left: 0;
			  border-right: 0;
			  min-width: 300px;
	    }
		}
	}
</style>