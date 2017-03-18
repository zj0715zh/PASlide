使用方法如下：

<!DOCTYPE html><br>
<html lang="en"><br>
<head><br>
<meta http-equiv="Content-Type" content="text/html; charset=utf-8" /><br>
<title>轮播+放大缩小功能</title><br>
<link rel="stylesheet" href="css/PASlide.css"><br>
</head><br>
<body><br>
	<div class="boxSlide"><br>
	  	<div id="featured"><br>
	      	<img src="images/overflow.jpg" /><br>
	        <img src="images/captions.jpg" /> <br>
	        <img src="images/features.jpg" /> <br>
	    </div><br>
		<div id="imgContainer"></div><br>
	</div><br>
<script src="js/jquery-1.11.0.min.js"></script><br>
<script src="js/slide.js"></script><br>
<script src="js/zoom.js"></script><br>
<script type="text/javascript"><br>
	$(window).load(function() {<br>
		$('#featured').PASlide({<br>
			timer:false,<br>
			animationSpeed:500,<br>
			animation:'horizontal-push',<br>
			resizeBox:'#imgContainer',<br>
		});<br>
	});<br>
</script><br>

此插件不仅具备图片轮播的效果，更是具有单图定向放大的功能，其中具体的轮播参数使用可以查看slide.js
