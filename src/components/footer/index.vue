<template>
  <footer id="foot">
			<ul>
				<router-link tag="li" to="/movie">
					<i class="iconfont icon-dianying"></i>
					<p>电影</p>
				</router-link>
				<router-link tag="li" to="/cinema">
					<i class="iconfont icon-yingyuan"></i>
					<p>影院</p>
				</router-link>
				<router-link tag="li" to="/mine">
					<i class="iconfont icon-wode"></i>
					<p>我的</p>
				</router-link>
			</ul>
		</footer>
</template>

<script>
export default {
  name:'foot'
}
</script>

<style scoped>
#foot{ width:100%; height:50px; background: white; border-top:2px #ebe8e3 solid; position: fixed; left: 0; bottom:0;}
#foot ul{ display: flex; text-align: center; height:50px; align-items:center;}
#foot ul li{ flex:1; height:40px;}
#foot ul li.active{ color: #f03d37;}
#foot ul li.router-link-active{ color: #f03d37;}
#foot ul i{ font-size: 20px;}
#foot ul p{ font-size: 12px; line-height: 18px;}
</style>