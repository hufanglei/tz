# 表单

## 表单

		表单是一个包含表单元素的区域。
		表单元素是允许用户在表单中（比如：文本域、下拉列表、单选框、复选框等等）输入信息的元素。
		<form  action="url" method=”post”>···input元素</form>

## 多行文本输入框(文本域)	
	
		<textarea name="file" rows=20 cols=30></textarea>
		cols，垂直列。
		在没有做样式表设置的情况下，它表示一行中可容纳下的字节数。
	    例如cols=60，表示一行中最多可容纳60个字节，也就是30个汉字
	    rows，水平行。表示可显示的行数， 
		例如rows=10，表示可显示10行。超过10行，则需要拖动滚动条来浏览了
		name，文本框的名称，这项必不可省，因为存储文本的时候必须用到。

## 表单元素

		单行文本输入框
			<input type="text"  name="txt" value="”/>   
			<input type=password” />
			name值     文本框的名称，这项必不可省，因为存储文本的时候必须用到。
			value值     文本输入框的默认值
		单选按钮（Radio Button）	
			当用户从若干给定的的选择中选取其一时，就会用到单选框。（多项选其一）
			<input type="radio"  name="sex"  value="0"/>男
			<input type="radio"  name="sex"  value="1"/> 女
			name名称必须相同。默认选择可加checked。
		复选框（Checkboxe）多选框
			当用户需要从若干给定的选择中选取一个或若干选项时，就会用到复选框。
			<input type="checkbox" name="apple" />苹果
			<input type="checkbox" name="banana" />香蕉	
					一、按钮标签
				<input type="button"  value="按扭值" /> 
				<input type="submit" value="登录" />
				<input type="reset" />
				二、隐藏输入框
				<input type="hidden" value=""  /> 
			三、文件域标签
				<input type="file" />
			四、定义域
				组合表单中的相关元素：
		             		<fieldset>
					<legend>定义域标题</legend>
				 	被组合的表单元素
		            		</fieldset>

## label

		Label标签定义和用法：
	    <label> 标签为 input 元素定义标注（标记）。
	    label 元素不会向用户呈现任何特殊效果。不过，它为鼠标用户改进了可用性。如果您在 label 元素内点击文本,就会触发此控件。就是说，当用户选择该标签时，浏览器就会自动将焦点转到和标签相关的表单控件上。
		<label> 标签的 for 属性应当与相关元素的 id 属性相同。
		<form>
		     <label for="male">Male </label><input type="radio"  name="sex"  id="male" />
		</form>

## 使用css制作三角形 见html代码		