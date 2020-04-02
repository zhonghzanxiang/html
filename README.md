<!DOCTYPE html>
<html>
	<head>
		<meta charset="utf-8">
		<title>个人主页</title>
		<style>/*布局设置 */
		body{/* 视频页面大小设置 */
		width:70%;/* 视频宽度 */
		height:65%;/* 视频高度 */
		text-align: center;
		background-color: #008000;
	
		</style>
	</head>
	<body >
		<header> <h1><a href=" "width="170" height="60">前端开发学习</a ></h1> 
		  
		  <p>看雪,是一种唯美的心境。这个冬季，放下疲惫的自己，一起看雪吧</p >
		  
		  <div class="b_nav"></div>
		  <div id="nav">
		    <ul>
		     <li><a href="https://music.163.com/"target="_blank" title="网易云音乐">网易云音乐</a ></li>
		      <li><a href="http://www.baidu.com" target="_blank" title="百度">百度</a ></li>
		      <li><a href="http://www.zptc.cn/" target="_blank" title="浙江邮电职业技术学院">浙江邮电职业技术学院</a ></li>
		      <li><a href="https://www.w3school.com.cn/" target="_blank" title="HTML W3school">HTML W3school</a ></li>
		      <li><a href="http://css.doyoe.com/" target="_blank" title="CSS3参考手册">CSS3参考手册</a ></li>
		      <li><a href="http://www.lmlblog.com/wo/life/man/" target="_blank" title="慢生活">慢生活</a ></li>
		      <li><a href="http://www.lmlblog.com/wo/newstalk/" target="_blank" title="碎言碎语">碎言碎语</a ></li>
		    </ul>
		  </div>
		
		<!--响应式图像-->
		<picture>
		 <source srcset="beijing.jpg" media="min-width:1000px">
		</picture>
		<!--浏览器兼容-->
		<picture>
		 <source type="image/svg+xml" srcset="beijing.jpg">
		 <source type="image/webp+xml" srcset="beijing.jpg">
		</picture>
		<iframe frameborder="no" border="0" marginwidth="0" marginheight="0" width=330 height=86 src="//music.163.com/outchain/player?type=2&id=1417650764&auto=1&height=66"></iframe>
		<!-- 例如使用iframe的方式调用网易云音乐 -->
		
	</body>
</html>
