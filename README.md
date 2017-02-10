# xjx_Slide
一个js Slide插件

### 介绍

来自慕课网课程 JS实现“旋转木马”幻灯片效果学习,用学习到的方式自己封装的js轮播插件




* 调用方法：

     引入css和main.js、jQuery
     
		
		Carousel.init($(".csl-container"));
		


* 配置方法：

	HTML最外层从.csl-container开始

 	在类名为.csl-container的节点设置data-setting属性，加上需要的配置属性和对应的值：例如
 
    ```
    <div class="csl-container clear" data-setting='{"width": "fullScreen","height": "500","speed": 500,"slideType": "normal"}'></div>
	```

	各配置项的意思：
	
		width: 图片宽//可接受像素数值和fullScreen
		height: 图片高,//可接受像素数值和fullScreen
		speed: 前后页切换速度,
		autoPlay: 自动切换时间间隔
	
	
	
