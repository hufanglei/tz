# css选择器初级和背景

## html命名规范


### 1. HTML命名规范

		名字尽量用英文小写字母
		可以包含字母,数字,中短线( - ),下划线( _ )
		有意义的命名(见名知意)

### 2. 企业命名规范:

		拓展: 		
		驼峰命名:第一个单词小写,第二单词首字母大写例:imgList

## css初级选择器
		
		一、通配符选择器
		二、元素选择器
		三、id选择器
		四、class类选择器
		五、ID选择器与Class选择器的区别
		六、包含(后代)选择器

## background背景样式
### background是简写属性，在一个声明中设置所有的背景属性：

		1.background-color:规定要使用的背景颜色
		2.background-image:把图像设为背景图片
		3.background-size:改变背景图片大小
			auto，cover, contain
		4.background-repeat:规定如何重复背景图片
		5.background-position：规定背景图片位置
		6.background-attachment:背景关联
		7.background:综合样式控制	

### background背景样式	

#### 1、background-color 背景颜色

		十六进制值  #CC0066	    #000
		英文单词里颜色值  red  gray blue yellow 
		Rgba 表达法   (css3)

#### 2、background-image 添加背景图片	

		url("地址")  引用背景图片的地址
		none  不使用背景图片	

#### 3. background-repeat  背景重复

		repeat:默认。背景图像在水平和垂直方向均重复
		repeat-x:背景图片在水平方向重复
		repeat-y:背景图片在垂直方向重复
		no-repeat:背景图片只显示一次，不重复		

#### 4. background-position 规定背景图像位置
##### ① 使用关键字：top、bottom、left、right 和 center两两组合而成
	
		ps:如果只出现一个关键字，则认为另一个关键字是 center

#####	②. 数字表达:一个对应水平方向，另一个对应垂直方向	
###### 1）百分数值  （水平%   竖直%)

		background-position：20% 30%；
		ps:如果只提供一个百分数值，所提供的这个值将用作水平值，垂直值将假设为50% 

###### 2）具体的值  （水平px   竖直px)

        background-position:20px 30px;

#### 5、background-attachment背景关联

		scroll(默认值)    fixed  inheri（继承父类）     

#### 6、background 综合样式控制	

	 	background: url("")   no-repeat   2px  5px; 	
		（路径 背景颜色 重复 位置;）

>还有一个注意点:

		背景定位的三种方式
		1.关键字
		   如:background-position:top left;/*垂直方向 水平方向
		   注意必须和background-attachment:fixed;配合使用
		2.百分数
		  如	background-position:100px 200px;/*水平方向 垂直方向
		  切记 :参数值的意思 顺序和关键字正好相反
		  注意必须和background-attachment:fixed;配合使用	
        3.实际像素
		 	background-position:100px 200px;/*水平方向 垂直方向
		   切记	 方向，这个不用关联background-attachment:fixed;
		


		







