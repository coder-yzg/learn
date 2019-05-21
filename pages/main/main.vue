<template>
	<view class="main">
		<block v-for="(item,index) in foodlist" :key="index"></block>
	</view>
</template>

<script>
	export default {
		data() {
			return {
				foodlist:[
					
				]
			}
		},
		methods: {
			
		}
	}
</script>

<style>

</style>
