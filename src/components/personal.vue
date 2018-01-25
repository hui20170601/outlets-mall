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
    <div class="personal-info">
      <div class="avatar fl">
        <img src="" alt="">
      </div>
      <div class="base-info fl">
        <p class="f-18">windir</p>
        <p class="f-12">已绑定微信账号</p>
        <p class="member-integral f-12">
          <span>黄金会员</span>
          <span>1800积分</span>
        </p>
      </div>
    </div>
    <ul class="extentions bgw" >
    		<li class="extentions-items">
					<img src="../assets/img/u2408.svg" alt="">
					<span class="mui-tab-label items-txt">我的订单</span>
				</li>
				<li class="extentions-items">
					<img src="../assets/img/u2420.svg" alt="">  
          <span class="extend-num get">1</span>
					<span class="mui-tab-label items-txt">待提货</span>
				</li>
				<li class="extentions-items">
					<img src="../assets/img/u2415.svg" alt="">
					<span class="mui-tab-label items-txt">已提货</span>
				</li>
				<li class="extentions-items">
					<img src="../assets/img/u2428.svg" alt="">
          <span class="extend-num assess">1</span>          
					<span class="mui-tab-label items-txt">待评价</span>
				</li>
  		</ul>
    <div class="settings">
      <div class="mui-table-view-cell">
        <i class="icon-heart fl f-14"></i>
			  <a class="mui-navigate-right fl">我的收藏</a>
		  </div>
      <div class="mui-table-view-cell">
        <i class=" icon-list-alt fl f-14"></i>
			  <a class="mui-navigate-right fl">门店信息</a>
		  </div>
      <div class="mui-table-view-cell">
        <i class="icon-cog fl f-16"></i>
			  <a class="mui-navigate-right fl">设置</a>
		  </div>
    </div>
    
	</div>
</template>

<script>
// import Mui from 'mui'
export default {
  name: "personal",
  data() {
    return {};
  },
  mounted() {
  }
};
</script>

<style scoped>
  .outlets-mall .personal-info {
    height: 2rem;
    box-sizing: border-box;
    padding:0.8rem 0 0 0.4rem;
    background-color: rgba(70, 76, 91, 1); 
    margin-bottom: 8px;
  }
  .personal-info .avatar {
    width: 0.8rem;
    height: 0.8rem;
    border-radius: 50%;
    background-color: beige;
    margin-right: 0.2rem;
  }
  .personal-info .base-info p {
    color: #fff;
  }
  .personal-info .base-info .member-integral {
    border: 1px solid rgb(243, 78, 106);
    border-radius: 18px;
    padding: 0 5px;
    color: rgb(243, 78, 106);
  }
  .outlets-mall .extentions {
		padding: 0.2rem 0 0.1rem;
		margin-bottom: 8px;
		text-align: center;
    display: flex;
    display: -webkit-flex;
    justify-content: space-around;
    -webkit-justify-content: space-around;
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
  .extentions-items .extend-num {
    position: absolute;
    width: 16px;
    height: 16px;
    line-height: 16px;
    border-radius: 50%;
    background-color: rgb(248, 82, 17);
    color: #fff;
    top: 2.25rem;
  }
  .extentions-items .get {
    left: 1.5rem;
  }
  .extentions-items .assess {
   right: 0.25rem;
  }
  .outlets-mall .settings {
    height: 3.2rem;
    background-color: rgb(249, 249, 249);
  }
  .mui-table-view-cell:after {
    height: 0;
  }
  .mui-navigate-right {
    width: 100%;
  }
  .mui-navigate-right:after {
    font-size: 24px;
  }
  .outlets-mall .settings .mui-table-view-cell {
    margin-bottom: 8px;
    background-color: #fff;
  }
  .settings .mui-table-view-cell i {
    margin: 3px 10px 0 0;
  }
</style>
