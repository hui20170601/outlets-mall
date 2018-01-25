<template>
	<div class="outlets-mall">
		<div class="mui-bar mui-bar-tab">
			<a class="mui-tab-item mui-active" href="#tabbar">
				<i class="icon-home f-24"></i>
				<span class="mui-tab-label">首页</span>
			</a>
			<a class="mui-tab-item" href="#tabbar-with-chat">
				<i class="icon-th-large"></i>
				<span class="mui-tab-label">分类</span>
			</a>
			<a class="mui-tab-item" href="#tabbar-with-contact">
				<i class="icon-gift"></i>
				<span class="mui-tab-label">会员权益</span>
			</a>
			<a class="mui-tab-item" href="#tabbar-with-map">
				<i class="icon-user"></i>
				<span class="mui-tab-label">个人中心</span>
			</a>
		</div>
		<div class="mui-content">
			<div id="slider" class="mui-slider slider">
				<div class="mui-slider-group mui-slider-loop">
					<div class="mui-slider-item mui-slider-item-duplicate">
						<a href="#">
							<img src="../assets/img/p4.jpg">
						</a>
					</div>
					<!-- 第一张 -->
					<div class="mui-slider-item">
						<a href="#">
							<img src="../assets/img/p1.jpg">
						</a>
					</div>
					<!-- 第二张 -->
					<div class="mui-slider-item">
						<a href="#">
							<img src="../assets/img/p2.jpg">
						</a>
					</div>
					<!-- 第三张 -->
					<div class="mui-slider-item">
						<a href="#">
							<img src="../assets/img/p3.jpg">
						</a>
					</div>
					<!-- 第四张 -->
					<div class="mui-slider-item">
						<a href="#">
							<img src="../assets/img/p4.jpg">
						</a>
					</div>
					<!-- 额外增加的一个节点(循环轮播：最后一个节点是第一张轮播) -->
					<div class="mui-slider-item mui-slider-item-duplicate">
						<a href="#">
							<img src="../assets/img/p1.jpg">
						</a>
					</div>
				</div>
				<div class="mui-slider-indicator">
					<div class="mui-indicator mui-active"></div>
					<div class="mui-indicator"></div>
					<div class="mui-indicator"></div>
					<div class="mui-indicator"></div>
				</div>
			</div>
			<ul class="extentions bgw" >
    		<li class="extentions-items">
					<img src="../assets/img/u246.svg" alt="">
					<span class="mui-tab-label items-txt">邀请好友</span>
				</li>
				<li class="extentions-items">
					<img src="../assets/img/u146.svg" alt="">
					<span class="mui-tab-label items-txt">服务专区</span>
				</li>
				<li class="extentions-items">
					<img src="../assets/img/u140.svg" alt="">
					<span class="mui-tab-label items-txt">红包</span>
				</li>
				<li class="extentions-items">
					<img src="../assets/img/u152.svg" alt="">
					<span class="mui-tab-label items-txt">签到</span>
				</li>
				<li class="extentions-items">
					<span class="mui-icon mui-icon-home items-icon"></span>
					<span class="mui-tab-label items-txt">首页</span>
				</li>
				<li class="extentions-items">
					<span class="mui-icon mui-icon-home items-icon"></span>
					<span class="mui-tab-label items-txt">首页</span>
				</li>
  		</ul>
			<div class="announcement bgw">
				<div class="announcement-info">
					<i class="icon-volume-up f-18"></i>
					<ul class="message f-12">
						<li>奥特莱斯成为中国最大的手机零食商</li>
					</ul>
				</div>
				<div class="details f-12">详情</div>
			</div>
			<div class="goods-pic clearfix bgw">
				<div>
					<img src="../assets/img/p4.jpg" alt="">
				</div>
				<div>
					<img src="../assets/img/p2.jpg" alt="">
				</div>
				<div>
					<img src="../assets/img/p3.jpg" alt="">
				</div>
			</div>
			<div class="hot-brand bgw">
				<div class="title clearfix">
					<span class="fl">热门品牌</span>
					<i class="icon-angle-right fr f-24"></i>
					<span class="fr">更多品牌</span>			
				</div>
				<ul class="hot-brand-tab">
					<li class="tab-active">苹果</li>
					<li>小米</li>
					<li>华为</li>
					<li>vivo</li>
					<li>oppo</li>
					<li>三星</li>
				</ul>
				<div class="hot-brand-content clearfix">
					<div class="tab-content fl">
						<div class="hot-brand-cell clearfix">
							<img src="../assets/img/p3.jpg" alt="" class="fl">
							<div class="fl txt">
								<p class="f-14">iphoneX</p>
								<p class="f-13 red">¥8888</p>
							</div>		
						</div>
						<div class="hot-brand-cell clearfix">
							<img src="../assets/img/p3.jpg" alt="" class="fl">
							<div class="fl txt">
								<p class="f-14">iphoneX</p>
								<p class="f-13 red">¥8888</p>
							</div>		
						</div>
						<div class="hot-brand-cell clearfix">
							<img src="../assets/img/p3.jpg" alt="" class="fl">
							<div class="fl txt">
								<p class="f-14">iphoneX</p>
								<p class="f-13 red">¥8888</p>
							</div>		
						</div>
						<div class="hot-brand-cell clearfix">
							<img src="../assets/img/p3.jpg" alt="" class="fl">
							<div class="fl txt">
								<p class="f-14">iphoneX</p>
								<p class="f-13 red">¥8888</p>
							</div>		
						</div>
					</div>
					<div class="tab-content fl">
						<div class="hot-brand-cell clearfix">
							<img src="../assets/img/p3.jpg" alt="" class="fl">
							<div class="fl txt">
								<p class="f-14">iphoneX</p>
								<p class="f-13 red">¥8888</p>
							</div>		
						</div>
						<div class="hot-brand-cell clearfix">
							<img src="../assets/img/p3.jpg" alt="" class="fl">
							<div class="fl txt">
								<p class="f-14">iphoneX</p>
								<p class="f-13 red">¥8888</p>
							</div>		
						</div>
						<div class="hot-brand-cell clearfix">
							<img src="../assets/img/p3.jpg" alt="" class="fl">
							<div class="fl txt">
								<p class="f-14">iphoneX</p>
								<p class="f-13 red">¥8888</p>
							</div>		
						</div>
						<div class="hot-brand-cell clearfix">
							<img src="../assets/img/p3.jpg" alt="" class="fl">
							<div class="fl txt">
								<p class="f-14">iphoneX</p>
								<p class="f-13 red">¥8888</p>
							</div>		
						</div>
					</div>
				</div>
			</div>
			<div class="recommend hot-brand bgw">
				<div class="title clearfix">
					<span class="fl">热门推荐</span>
					<i class="icon-angle-right fr f-24"></i>
					<span class="fr">更多推荐</span>			
				</div>
				 <div class="goods-info">
        	<div class="content">
						<img class="mui-media-object mui-pull-left" src="../assets/img/p3.jpg">
						<div class="mui-media-body f-16 block fl">
							苹果 iphone7
							<p class='recommend-list-txt f-12 block'>防水防尘，混合红外线滤镜，TrueTone 闪光灯</p>
							<p class='mui-ellipsis f-13 red'>¥4079</p>
							<p class='mui-ellipsis f-12 block'>(门店自提）广州白云区店</p>
						</div>
        	</div>
        	<div class="content  clearfix">
						<img class="mui-media-object mui-pull-left" src="../assets/img/p3.jpg">
						<div class="mui-media-body f-16 block">
							苹果 iphone7
							<p class='recommend-list-txt f-12 block'>防水防尘，混合红外线滤镜，TrueTone 闪光灯</p>
							<p class='mui-ellipsis f-13 red'>¥4079</p>
						</div>
        	</div>
      	</div>
			</div>
		</div>
	</div>
</template>

<script>
// import Mui from 'mui'
export default {
  name: "home",
  data() {
    return {};
  },
  mounted() {
    // mui.plusReady(function(){
    mui.init({
      swipeBack: true //启用右滑关闭功能
    });
    var slider = mui("#slider");
    // slider.slider({
    // 	interval: 2000
    // });
		// });
	
  }
};
</script>

<style scoped>
	.outlets-mall .slider {
  	height: 2rem;
	}
	.outlets-mall .extentions {
		overflow-x: scroll;
		white-space: nowrap;
		padding: 0.2rem 0 0.1rem;
		margin-bottom: 8px;
		text-align: center;
	}
	.outlets-mall .extentions li:first-child {
		margin-left: 0.4rem
	}
	.outlets-mall .extentions .extentions-items{
		display: inline-block;
		margin-left: 0.45rem;
	}
	.extentions .extentions-items img {
		width: 0.3rem;
	}
	.extentions .extentions-items span {
		display: block;
	}
	.extentions .extentions-items .items-txt {
		text-align: center;
	}
	.extentions .extentions-items .items-icon {
		font-size: 36px;
		margin-bottom: 5px;
	}
	.outlets-mall .announcement {
		display: flex;
		display: -webkit-flex;
		align-items: center;
		-webkit-align-items: center;
		justify-content: space-between;
		-webkit-justify-content: space-between;
		height: 0.4rem;
		line-height: 0.4rem;
		padding: 0 0.2rem;
		margin-bottom: 8px;		
	}
	.outlets-mall .announcement .announcement-info {
		display: flex;
		display: -webkit-flex;
		align-items: center;
		-webkit-align-items: center;
	}
	.announcement-info i {
		margin-right: 0.1rem;
	}
	.outlets-mall .announcement .mui-icon {
		font-size: 16px;
		margin-right: 10px;
	}
	.outlets-mall .announcement .details{
		width: 0.4rem;
		height: 0.2rem;
		line-height: 0.2rem;		
		border: 1px solid rgb(26, 188, 156);
		color: rgb(26, 188, 156);
		text-align: center;
		border-radius: 3px;
	}
	.outlets-mall .goods-pic {
		padding: 0.1rem;
		margin-bottom: 8px;
	}
	.outlets-mall .goods-pic div {
		width: 1.72rem;
	}
	.outlets-mall .goods-pic div img {
		width: 100%;
		height: 100%;
	}
	.outlets-mall .goods-pic div:first-child {
		height: 2rem;
		margin-right: 0.1rem;
		float: left;
	}
	.outlets-mall .goods-pic div:nth-child(2) {
		height: 0.95rem;
		float: left;
		margin-bottom: 0.1rem;		
	}
	.outlets-mall .goods-pic div:last-child {
		height: 0.95rem;
		float: left;		
	}
	.outlets-mall .hot-brand {
		padding: 0.1rem;
		overflow: hidden;	
		margin-bottom: 8px;	
	}
	.outlets-mall .title {
		line-height: 36px;
		border-bottom: 1px solid #c8c7cc;
	}
	.outlets-mall .title i {
		line-height: 36px;
		margin-left: 0.1rem;
	}
	.outlets-mall .hot-brand .hot-brand-tab {
		display: flex;
		display: -webkit-flex;
		height: 44px;
		line-height: 44px;
	}
	.hot-brand .hot-brand-tab li {
		display: inline-block;
		margin-right: 0.15rem;
		padding: 0 0.1rem;
		padding: 0 5px;
	}
	.hot-brand .hot-brand-tab .tab-active {
		color: rgba(26, 188, 156, 1);
    height: 42px;
    border-bottom: 3px solid rgba(26, 188, 156, 1);
	}
	.hot-brand .hot-brand-content {
		margin-top:12px;
		background-color: #efeff4;
		width: 1000%;
	}
	.hot-brand-content .tab-content {
		display: flex;
		display: -webkit-flex;
		width: 3.4rem;
		flex-wrap: wrap;
	}
	.tab-content div:first-child, .tab-content div:nth-child(2) {
		margin-bottom: 5px
	}
	.hot-brand .hot-brand-content .hot-brand-cell {
		width: 1.64rem;
		background-color: #fff;
		margin-right: 5px;
	}
	.hot-brand-content .hot-brand-cell img {
		width: 55%;
		height: 80px;
	}
	.hot-brand-content .hot-brand-cell .txt {
		padding: 0.15rem 0 0 0.1rem;
	
	}
	.outlets-mall .recommend .title {
		padding-bottom: 10px;
	}
	.recommend .recommend-list .recommend-list-txt{
		width: 240px;
		white-space: normal;
	}
	.goods-info .content {
		height: 1.21rem;
	}
</style>
