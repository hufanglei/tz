#  样式+div盒子模型 知识点


### 1. 引用外部引用表的时候，注意外部样式的 编码，特别是分号

		@charset "utf-8";
		div{
			font-size: 40px;
			color:red
		}


### 2. 内外边距可以用 百分数，该长度是 父级的 百分数
		
		注意：百分数为 父亲盒子的百分数
		1、margin-top 	上面(顶部)外边距
		      margin-top:20px;        或  padding-top:10%;
		2、 margin-right	  右边外边距
		      margin-right:20px;      或  padding-right:10%;
		3、margin-bottom   下面(底部)外边距
		     margin-bottom:20px;  或  padding-bottom:10%;
		4、margin-left	左边外边距
		     margin-left:20px;         或  padding-top:10%;


### 3. 样式box-sizing的使用

		border-box：表示长度高度固定，边框内边距都外内部挤
		content-box:默认
		inherit：继承父类的规格

### 4. 边框的几个线的样式 边框样式值
		
		none     无边框   
		solid    实线
		dashed   虚线
		dotted   点状 
		double   双线
		groove   3D凹槽边框
		ridge    3D垄状边框
		inset    3Dinset 边框
		outset   3Doutset 边框 
		