<template>
	<!-- view类似传统div -->
	<view hover-class="boxHover1" hover-start-time="2000" hover-stay-time="4000">
		demo1
		<view hover-stop-propagation="true  "  hover-class="boxHover" hover-start-time="2000" hover-stay-time="4000">
			child
		</view>
	</view>
</template>

<script>
	export default {
		data() {
			return {
				
			};
		}
	}
</script>

<style lang="scss">
.boxHover1{
	background-color: lemonchiffon;
}
.boxHover{
	background-color: lightcoral;
}
</style>
