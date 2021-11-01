<template>
	<view style="height: 100%;">
		<view class="flex-item flex-item-V-first">A</view>
		<view class="flex-item flex-item-V-second uni-bg-green">B</view>
		<view class="flex-item flex-item-V-third uni-bg-blue">C</view>
		<view class="flex-item flex-item-V-fourth uni-bg-green">D</view>
	</view>
</template>

<script>
	export default {
		data() {
			return {
				title: 'Hello'
			}
		},
		onLoad() {

		},
		methods: {

		}
	}
</script>

<style>
	.content {
		display: flex;
		flex-direction: column;
		align-items: center;
		justify-content: center;
	}

	.logo {
		height: 200rpx;
		width: 200rpx;
		margin-top: 200rpx;
		margin-left: auto;
		margin-right: auto;
		margin-bottom: 50rpx;
	}

	.text-area {
		display: flex;
		justify-content: center;
	}

	.title {
		font-size: 36rpx;
		color: #8f8f94;
	}

	.flex-item {
		width: 33.3%;
		height: 200rpx;
		text-align: center;
		line-height: 200rpx;
	}

	.flex-item-V-first {
		width: 100%;
		height: 10%;
		text-align: center;
		line-height: 100rpx;
	}
	
	.flex-item-V-second {
		width: 100%;
		height: 10%;
		text-align: center;
		line-height: 100rpx;
	}
	
	.flex-item-V-third {
		width: 100%;
		height: 60%;
		text-align: center;
		line-height: 150rpx;
	}
	
	.flex-item-V-fourth {
		width: 100%;
		height: 20%;
		text-align: center;
		line-height: 150rpx;
	}
	

	.text {
		margin: 15rpx 10rpx;
		padding: 0 20rpx;
		background-color: #ebebeb;
		height: 70rpx;
		line-height: 70rpx;
		text-align: center;
		color: #777;
		font-size: 26rpx;
	}

	.desc {
		/* text-indent: 40rpx; */
	}
	.flex-pc {
		display: flex;
		justify-content: center;
	}
</style>
