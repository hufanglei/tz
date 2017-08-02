# 准备:
    学习如何使用 sublimeTEXT3 自定义模板
    ![参考地址](http://www.fantxi.com/blog/archives/sublime-template-engine-sublimetmpl/)


# 1. html（HyperText Markup Language ）
是一种由标签组成的超文本标记语
	言，而非编程语言, 一个html文档就是一个网页。
	
 ## html标签：
	- 1)HTML 标记标签通常被称为 HTML 标签 (HTML tag)。
	- 2)html标签由尖括号组成的关键词,比如<html>
	- 3)html标签成对出现,第一个开始(开放)标签,第二个结束(闭合)
	- 标签,比如<head></head>标签必须闭合，单标签加”/“闭合

   ##   html文档=网页：
	- 1)html文档描述网页
    - 2)html文档包含html标签和纯文本
	- 3)浏览器不会显示 HTML 标签，而是使用标签来解释页面的内容



	 
   ##  h1-h6 : 标题标签

		<h1>标题标签</h1>
		<h3>还是标题标签</h3>
	    font标签：字体效果标签    (淘汰）
	    <font>要显示的文字</font>
	    color:字体颜色
	    size:字体大小 (1-7)
	    p标签：段落标签
		<p>这是段落标签</p>


## pre标签：定义预格式化文本

        <pre>文字格式按源码显示</pre>
        <pre>常用来显示代码</pre>


## em/i标签：强调标签,都是斜体标签，em有利于seo优化，i和seo没关系

	<em>这是强调标签</em>
        <em>被它强调文字斜体显示</em>
        <i>这是斜体标签</i>
       

## strong/b标签:加粗标签，strong有利于seo优化，b和seo没关系

        <strong>粗体文本，强调程度强，重要文本</strong>
        <b>文本呈现粗体效果</b>


## del标签：删除标签

        <del>定义文档中已经被删除的文本</del>


 ## ins标签  :  插入标签

         <ins>定义被插入文本</ins> 


 ## a标签： 超链接标签
	<a href=””>要显示的文字</a>
	target属性 以什么方式打开这个链接
	_self 默认当前页面刷新
	_blank 重新开一个窗口打开


	 锚点：链接到同一个页面的不同的位置
	 a href=”#锚点名称” a name=”锚点名称”
	 电子邮件链接：< a href=”mailto:邮箱地址”>邮箱</a>   
    



