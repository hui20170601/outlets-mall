<template>
	<div class="outlets-category">
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
      <div class="search bd bgw">
        <div class="mui-input-row">
					<input type="text" placeholder="输入商品关键词或用户名" class="search-box f-12">
          <button type="button" class="mui-btn mui-btn-primary mui-icon mui-icon-search">搜索</button>          
				</div>
      </div>
      <div class="category-list clearfix bgw">
        <ul class="list-tab fl">
          <li class="bd">新品</li>
          <li class="list-tab-active bd">苹果</li>
          <li class="bd">小米</li>
          <li class="bd">华为</li>
          <li class="bd">三星</li>
          <li class="bd">oppo</li>
          <li class="bd">vivo</li>
          <li class="bd">配件</li>
          <li class="bd">oppo</li>
          <li class="bd">vivo</li>
          <li class="bd">配件</li>
          <li class="bd">vivo</li>
          <li class="bd">配件</li>
          <li class="bd">oppo</li>
          <li class="bd">vivo</li>
          <li class="bd">配件</li>
        </ul>
        <div class="list-content fl">
          <div class="list-content-items">
            <div class="list-content-info">
              <img src="../assets/img/p1.jpg" alt="">
              <p class="f-12 block">iphone7</p>
            </div>
            <div class="list-content-info">
              <img src="../assets/img/p2.jpg" alt="">
              <p class="f-12 block">iphone7</p>
            </div>
            <div class="list-content-info">
              <img src="../assets/img/p3.jpg" alt="">
              <p class="f-12 block">iphone7</p>
            </div>
          </div>
          <div class="list-content-items">
            <div class="list-content-info">
              <img src="../assets/img/p1.jpg" alt="">
              <p class="f-12 block">iphone7</p>
            </div>
            <div class="list-content-info">
              <img src="../assets/img/p2.jpg" alt="">
              <p class="f-12 block">iphone7</p>
            </div>
            <div class="list-content-info">
              <img src="../assets/img/p3.jpg" alt="">
              <p class="f-12 block">iphone7</p>
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
  name: "category",
  data() {
    return {};
  },
  mounted() {
  }
};
</script>

<style scoped>
  .outlets-category {
    /*height: 100%;*/
  }
	.outlets-category .search {
    padding: 0.1rem 0.2rem 0 0.1rem;
  }
  .outlets-category .search .search-box {
    width: 75%;
    margin-bottom: 0.1rem;
  }
  .outlets-category .search button {
    width: 21%;
    padding: 0.1rem 0.1rem;
    border: 1px solid rgb(26, 188, 156);
    background-color: rgb(26, 188, 156);
  }
  .category-list .list-tab {
    width: 25%;
    text-align: center;
    height: 5.5rem;
    box-sizing: border-box;
    overflow-y: scroll;
  }
  .category-list .list-tab li{
    height: 0.5rem;
    line-height: 0.5rem;
  }
  .category-list .list-tab .list-tab-active {
    color: rgba(26, 188, 156, 1);;
  }
  .category-list .list-content {
    width: 75%;
    border-left: 1px solid rgba(228, 228, 228, 1);   
    height: 5.5rem;
    overflow-y: scroll; 
  }
  .list-content .list-content-items {
    display: flex;
    display: -webkit-flex;
    padding-top: 0.1rem;
  }
  .list-content .list-content-items .list-content-info {
    flex: 1;
    text-align: center;
  }
  .list-content-items .list-content-info img {
    margin: 0 auto;
    width: 0.7rem;
    height: 0.9rem;
  }
</style>
