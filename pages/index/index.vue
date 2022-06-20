<template>
	<view class="main">
		<view class="main_top">	
		</view>
		<view class="main_content">
			<view class="content">
				<view class="content_left">
					知识详解
				</view>
				<view class="content_right">
					<view>遵循大纲突出重点</view>
					<view>知识梳理全面直观</view>
				</view>
			</view>
		</view>
	</view>
</template>

<script>
	export default {
		data() {
			return {
				
			}
		},
		onLoad() {

		},
		methods: {

		}
	}
</script>

<style scoped>
	.main_top{
		width: 100vh;
		height: 260rpx;
		background-color: black;
	}
	.main_content{
		display: flex;
		flex-wrap: wrap;
		justify-content: center;
	}
	.content{
		margin-top: 20rpx;
		width: 700rpx;
		height: 260rpx;
		background-color: #007AFF;
		border-radius: 40rpx;
		display: flex;
	}
	.content_left{
		flex: 1;
		font-size: 50rpx;
		position: relative;
		left:70rpx;
		margin-top: 80rpx;
	}
	.content_right{
		flex:1;
		position: relative;
		font-size: 30rpx;
		margin-top: 80rpx;
		margin-left:70rpx;
	}
</style>
