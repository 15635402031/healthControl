<template>
	<view>
		<!-- 显示图标 -->
		<view class="nav">
				<image  src="../../static/logo.png"></image>
				<view class="name" style="color: #FFFFFF;font-size:40rpx;">姓名</view>
				<view class="biao">企业负责人</view>
				<text>15612341234</text>
				<view class="right">
					>
				</view>
		</view>
		
		<uni-notice-bar showIcon="true" text="这是NoticeBar通告栏" class="message" style="background-color: #FFFFFF;"></uni-notice-bar>
	</view>	
	
	
</template>

<script>
	import uniNoticeBar from '@/components/uni-notice-bar/uni-notice-bar.vue'
	export default {
		data() {
			return {
				
			}
		},
		methods: {
			
		},
		components: {uniNoticeBar}
	}
</script>

<style scoped lang="scss">
		view{
			.nav{
				width:750rpx;
				height:276rpx;
				background:linear-gradient(225deg,rgba(70,168,255,1) 0%,rgba(148,159,254,1) 100%);
				opacity:1;
				overflow: hidden;
					.name{
						margin-top: 74rpx;
						float: left;
					}
					image{
						width: 122rpx;
						height: 122rpx;
						background-color: #eeeeee;
						margin:  70rpx 30rpx;
						float: left;
					}
					.biao{
						color: #FFFFFF;
						width: 136rpx;
						height: 35rpx;
						background-color: #FFC527;
						border-radius: 26px;
						float: left;
						font-size: 20rpx;
						text-align: center;
						margin-top: 83rpx;
						margin-left: 24rpx;
						padding-top: 5rpx;
					}
					span{
						position: absolute;
						left: 184rpx;
						top: 138rpx;
						color: #FFFFFF;
					}
					.right{
						color: #FFFFFF;
						position: absolute;
						right: 20rpx;
						top: 90rpx;
					}
			}
			/deep/.message{
				width:692rpx;
				height:86rpx;
				background:rgba(255,255,255,1);
				border:1rpx solid rgba(230,230,230,1);
				box-shadow:0rpx 6rpx 12rpx rgba(225,225,225,0.3);
				opacity:1;
				margin: 0,auto;
				border-radius:16px;
				margin-bottom: 20rpx;
				position: absolute;
				top: 118px;
				left: 12px;
			}
			text{
				color: red;
			}
		}
	
</style>
