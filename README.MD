# 表格+框架

## 表格

		表格：由 <table> 标签来定义。
		每个表格均有若干行（由 <tr> 标签定义）<tr></tr>
		每行被分割为若干单元格（由 <td> 标签定义）<td></td>
		数据单元格可以包含:
		(文本、图片、列表、段落、表单、水平线、表格) 等等。
		<table>
			<tr><td>1-1</td><td>1-2</td></tr>
			<tr><td>2-1</td><td>2-2</td></tr>
		</table>

## <table>的默认特征
		
		1、单元格默认平分table 的宽度
		2、th里面的内容默认加粗并且左右上下居中
		3、td里面的内容默认上下居中 左对齐显示
		4、 table 决定了整个表格的宽度；
		5、table里面的单元格宽度会被转换成百分比；
		6、 表格里面的每一列必须有宽度；
		7、表格同一列/行会继承最大值；
		8、th,td没有margin属性	

## table css表格样式：

		表格边框（border）
		合并边框（border-collapse:collapse）
		表格宽度和高度（width，height）
		表格文本对齐（text-align）
		表格颜色
		colspan="2"  表格单元横跨两列的表格(合并两列)
		rowspan="2" 表格单元纵跨两行的表格（合并两行）

##  五、display:table的特征

		table的标签类型：display:table;
		支持margin:auto;
		默认内容撑开宽度；
		支持宽高
		表格前后带有换行符。	

## iframe内联框架

		1、iframe 是个内联框架（内嵌框架），是在页面（body）里生成个内部框架
		2、iframe的属性
			width 		定义iframe的宽度；
			height 		定义iframe的高度；
			frameborder   	规定是否显示框架周围的边框  ,可能的值: 0无    1有
			src		规定在框架中显示的文档的 URL。
			scrolling  		规定是否在框架中显示滚动条。
							yes	显示滚动条		
							no	无
							auto	根据内容自动显示滚动条
			name		规定框架的名称	
		3、您可以把需要的文本放置在 <iframe> 和 </iframe> 之间，这样就可以应对无法理解 iframe  的浏览器	

## frame子框架

		frameborder属性
		a、frameborder  规定是否显示框架周围的边框。
			frameborder 可能的值：0	无    1 	有
		 	注意事项：需上下两子框架同时设置
		b、src	规定在框架中显示的文档的 URL	
		c、scrolling   规定是否在框架中显示滚动条同 iframe框架
		d、name	规定框架的名称	

## frameset框架集

		、frameset属性	
        a、frameset元素可定义一个框架集 可包含多个子框架，每个框架都有独立的文档。 
        b、frameset标签有一个必需的属性：rows | cols 
		1)、rows ：定义框架集中子框架 行的数目和尺寸（列展示）
		2)、cols ：定义框架集中子框架 列的数目和尺寸（横排展示）
		3)、单位值：
			pixels	像素
			%	百分比
			*	余下的
			rows="30%,*" ;表示子框架按行的样式布局,并且是2行，
			表示第一个框架占整个页面30%的高度，第二个占剩下的；
        c、noresize="noresize" 	整体设置子框架是否可调整范围。
        d、frameborder   		整体设置子框架的边框	
		3、frameset框架可以包含frameset
		2、框架
   		1、水平框架  2、垂直框架  3、混合框架结构  4、导航框架  5、带节点的框架

> 框架案例见html代码   		


			