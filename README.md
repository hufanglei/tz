# 优先级+css3

## 基本选择器优先级

		*{}
		tagName{}
		.className{}
		#idName{}
		总结 :    *  <   标签    <     class   <   id	

## 选择器优先级

		复杂选择器优先级
	    1）从高高低顺序依次是: ID选择器 class选择器 tagName{} 
	    2）ID选择器个数不相等，ID个数多的优先级高，后面不用比
	    3）ID选择器个数相等，则看class个数
	    4）class 个数相等 ，再看tagName 个数
	    5）#wrap ul li .list{} 和.wrap ul li #list{}优先级一样(不分先后)	

## 样式优先级

		行内样式	<div style=””></div>
	    内部样式	<style type=''text/css''></style>
	    外部样	<link rel="stylesheet" type="text/css" href=" "/>    
	    优先级:行内>内部>外部

## 常用css3

### border-radius圆角
		border-radius多种写法
		四个值：	左上   右上    右下    左下
		三个值：	左上   右上左下   右下
		两个值：	左上右下    右上左下 
		一个值：	所有角一样的值
		备注:画椭圆和圆的话，直接设置成border-radius:50%即可	 

### box-shadow阴影

		h-shadow	水平偏移量。允许负值	（必需）
		v-shadow	垂直偏移量。允许负值	（必需）
		blur		模糊半径	（可选。）
		spread		阴影的大小	（可选。）
		color		阴影的颜色	（可选。）	
		outset 		外部阴影	（默认）内部阴影 (inset)(可选)		

### overflow

	overflow内容溢出
	A 、overflow可能的值
		visible	默认值
		hidden	隐藏，并且其余内容是不可见的。
		scroll	出现滚动条
		auto	根据内容情况来决定（是否）出现滚动条
		scroll和auto的区别是 出现超出的话才显示滚动条，而scroll是无论何时,都会出现x和y方向滚动条
	B 、overflow-x
	C、 overflow-y

			

		