# img特征,vertical-align,cursor,opacity 

## img特征
		
		一、img特征
		1、重新认识img(特征)：
			A、支持宽高	
			B、支持margin
			C、（横排展示）
			D、能设置text-align
			E、 能设置vertical-align
		问题：	标签中间隙被解析
				不支持margin：auto;

## vertical-align

		二、vertical-align 垂直对齐方式
		1、定义行内元素的基线相对于该元素所在行的基线的垂直对齐。
		2、inline  inline-block    img图片标签才具有,块级元素没有
		3、vertical-align 可能的值：
		top		元素的顶端与行中最高元素的顶端对齐
		middle		此元素放置在父元素的中部。
		bottom		元素的顶端与行中最低的元素的顶端对齐。
		总结：以上值与line-height相关
		text-top		元素的顶端与父元素字体的顶端对齐
		text-bottom	把元素的底端与父元素字体的底端对齐。
		baseline		默认。元素放置在父元素的基线上。
		总结：以上值与font-size相关
		注意:	a、加vertical-align的同排元素都要vertical-align；
		b、vertical-align可以解决img下方间隙问题	

## cursor

		三、cursor指针样式
		1、cursor 指针样式 （规定要鼠标进入元素内容区域要显示的光标的类型）
		2、Cursor 可能的值：
			default		默认光标（通常是一个箭头）
			auto		默认。浏览器设置的光标。
			pointer		光标呈现为指示链接的指针（一只手）
			move		此光标指示某对象可被移动。
			text		光标指示文本。
			wait		光标指示正忙（通常是一只表或沙漏）。
			help		光标指示帮助（通常是一个问号或一个气球）
	 
		3、cursor:url(hand.cur),pointer;
			第一个值：Url() 定义指针文件路径，此文件得是cur后缀
			第二个值：当第一个值出错的时的备用类型	

##  opacity
		
		四、opacity透明度
		1、opacity 属性设置元素的不透明级别
		A 、标准 不透明度：  opacity:0~1; 
			从 0（完全透明）
			到 1（完全不透明）
		B、IE 滤镜（兼容IE下不支持opacity的版本）：  filter:alpha(opacity=0~100);
			从 0（完全透明）
			到 100（完全不透明）						