使用方法如下：
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

此插件不仅具备图片轮播的效果，更是具有单图定向放大的功能，其中具体的轮播参数使用可以查看slide.js
