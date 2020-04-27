<script>
	/* App.vue 应用程序启发 */
	export default {
		onLaunch: function() {//表示应用程序启动时
			console.log('App Launch')
		},
		onShow: function() {//页面显示时  onLoad()表示页面加载完毕时
			console.log('App Show')
		},
		onHide: function() {
			console.log('App Hide')
		}
	}
</script>

<style>
	/*每个页面公共css */
</style>
