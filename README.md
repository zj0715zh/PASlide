使用方法如下：

<!DOCTYPE html>
<html lang="en">
<head>
<meta http-equiv="Content-Type" content="text/html; charset=utf-8" />
<title>轮播+放大缩小功能</title>
<link rel="stylesheet" href="css/PASlide.css">
</head>
<body>
	<div class="boxSlide">
	  	<div id="featured">
	      	<img src="images/overflow.jpg" />
	        <img src="images/captions.jpg" /> 
	        <img src="images/features.jpg" /> 
	    </div>
		<div id="imgContainer"></div>
	</div>
<script src="js/jquery-1.11.0.min.js"></script>
<script src="js/slide.js"></script>
<script src="js/zoom.js"></script>
<script type="text/javascript">
	$(window).load(function() {
		$('#featured').PASlide({
			timer:false,
			animationSpeed:500,
			animation:'horizontal-push',
			resizeBox:'#imgContainer',//放大缩小的盒子ID
		});
	});
</script>
</body>
</html>

具体的轮播参数使用可以查看slide.js
