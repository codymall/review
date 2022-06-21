<template>
	<view class="main_content">
		<view class="content">
			<view class="content_left">
				<slot name="left"></slot> 
			</view>
			<view class="content_right" name="right">
				<view>
					<slot name="right_top"></slot>
				</view>
				<view>
					<slot name="right_bottom"></slot>
				</view>
			</view>
		</view>
	</view>
</template>

<script>
	export default {
		name: "content",
		data() {
			return {

			};
		}
	}
</script>

<style scoped>
	.main_content {
		display: flex;
		flex-wrap: wrap;
		justify-content: center;
		flex-direction: column;
		align-items: center;
	}

	.content {
		margin-top: 20rpx;
		width: 700rpx;
		height: 260rpx;
		background-color: #007AFF;
		border-radius: 40rpx;
		display: flex;
		color: white;
	}

	.content_left {
		flex: 1;
		font-size: 50rpx;
		position: relative;
		left: 70rpx;
		line-height: 260rpx;
		font-weight: bold;
	}

	.content_right {
		position: relative;
		font-size: 30rpx;
		font-style: italic;
		flex: 1;
		padding-top: 86rpx;
		margin-left: 80rpx;
	}
</style>
