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
			<div class="announcement bgw">
				<div class="announcement-info">
					<i class="icon-volume-up f-18"></i>
					<ul class="message f-12">
						<li>奥特莱斯成为中国最大的手机零食商</li>
					</ul>
				</div>
				<div class="details f-12">详情</div>
			</div>
			<div class="goods-pic clearfix">
				<div class="member-goods">
					<img src="../assets/img/p1.jpg" alt="">
					<div class="red">2000积分</div>
				</div>
        <div class="member-goods">
					<img src="../assets/img/p2.jpg" alt="">
					<div class="red">¥9.00+500积分</div>					
				</div>
				<div class="member-goods">
					<img src="../assets/img/p3.jpg" alt="">
				</div>
				<div class="member-goods">
					<img src="../assets/img/p4.jpg" alt="">
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
								<p class="f-14 block">iphoneX</p>
								<p class="f-13 red">¥8888</p>
							</div>		
						</div>
						<div class="hot-brand-cell clearfix">
							<img src="../assets/img/p3.jpg" alt="" class="fl">
							<div class="fl txt">
								<p class="f-14 block">iphoneX</p>
								<p class="f-13 red">¥8888</p>
							</div>		
						</div>
						<div class="hot-brand-cell clearfix">
							<img src="../assets/img/p3.jpg" alt="" class="fl">
							<div class="fl txt">
								<p class="f-14 block">iphoneX</p>
								<p class="f-13 red">¥8888</p>
							</div>		
						</div>
						<div class="hot-brand-cell clearfix">
							<img src="../assets/img/p3.jpg" alt="" class="fl">
							<div class="fl txt">
								<p class="f-14 block">iphoneX</p>
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
			<div class="hot-brand recommend clearfix bgw">
				<div class="title clearfix">
					<span class="fl">热门推荐</span>
					<i class="icon-angle-right fr f-24"></i>
					<span class="fr">更多推荐</span>			
				</div>
				<div class="recommend-items bd fl">
          <img src="../assets/img/p1.jpg" alt="">
          <p class="block">苹果iPhone7</p>
          <p class="f-13 red">¥1500+5000积分</p>
          <p class="f-12 block">市场参考价： ¥4999</p>
        </div>
        <div class="recommend-items bd fl">
          <img src="../assets/img/p2.jpg" alt="">
          <p class="block">苹果iPhone7</p>
          <p class="f-13 red">¥1500+5000积分</p>
          <p class="f-12 block">市场参考价： ¥4999</p>
        </div>
        <div class="recommend-items bd fl">
          <img src="../assets/img/p3.jpg" alt="">
          <p class="block">苹果iPhone7</p>
          <p class="f-13 red">¥1500+5000积分</p>
          <p class="f-12 block">市场参考价： ¥4999</p>
        </div>
        <div class="recommend-items bd fl">
          <img src="../assets/img/p4.jpg" alt="">
          <p class="block">苹果iPhone7</p>
          <p class="f-13 red">¥1500+5000积分</p>
          <p class="f-12 block">市场参考价： ¥4999</p>
        </div>
			</div>
		</div>
	</div>
</template>

<script>
// import Mui from 'mui'
export default {
  name: "member",
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
		margin: 8px 0;		
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
	.outlets-mall .goods-pic .member-goods {
		width: 1.72rem;
		height: 1.2rem;	
		float: left;	
		background-color: #fff;
		text-align: center;
	}
	.outlets-mall .goods-pic .member-goods img {
		display: block;
		width: 100%;
		height: 75%;
	}
	.outlets-mall .goods-pic .member-goods div {
		height: 25%;
		line-height: 30px;
	}
	.goods-pic div:first-child , .goods-pic div:nth-child(3){
		margin-right: 0.1rem;
	}
	.goods-pic div:first-child, .goods-pic div:nth-child(2) {
		margin-bottom: 0.1rem;		
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
	.goods-info .content {
		height: 1.21rem;
	}
	.outlets-mall .recommend .recommend-items {
		width: 50%;
		text-align: center;
		padding: 0.2rem 0;
	}
	.recommend .recommend-items img {
		width: 120px;
		height: 120px;
		margin-bottom: 10px;
	}
</style>
