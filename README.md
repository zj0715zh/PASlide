使用方法如下：
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
