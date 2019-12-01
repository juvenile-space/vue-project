<template>
  <div class="index" >
    <h1>这是 App 组件</h1>
     <mt-header fixed title="杨瑞小铺"></mt-header>
    <!-- <mybtn type="primary">12345</mybtn> -->
   <nav class="mui-bar mui-bar-tab">
			<a class="mui-tab-item mui-active" href="#tabbar">
				<span class="mui-icon mui-icon-home"></span>
				<span class="mui-tab-label">首页</span>
			</a>
			<a class="mui-tab-item" href="#tabbar-with-chat">
				<span class="mui-icon mui-icon-contact"></span>
				<span class="mui-tab-label">会员</span>
			</a>
			<a class="mui-tab-item" href="#tabbar-with-contact">
				<span class="mui-icon mui-icon-extra mui-icon-extra-cart "><span class="mui-badge">0</span></span>
				<span class="mui-tab-label">购物车</span>
			</a>
			<a class="mui-tab-item" href="#tabbar-with-map">
				<span class="mui-icon mui-icon-search"></span>
				<span class="mui-tab-label">搜索</span>
			</a>
		</nav>
  </div>
</template>

<script>
// 按需导入 Toast 组件
import { Toast } from "mint-ui";

export default {
}
</script>


<style lang="scss" scoped>
.index {
  padding-top: 40px;
}
</style>>


