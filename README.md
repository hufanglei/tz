# css样式(font+text)+特殊符号

## 1.css控制字体
	
			一、color 控制字体颜色
				1、十六进制值  #CC0066	    #000
				2、颜色单词
			二、font-size 控制字体大小
				单位:    px	像素
				%	相对于父元素    
				em      取决自己使用字体大小                
				rem	取决于根元素html的字体大小

			三、font-family 控制字体的类型
				font-family:"黑体";（默认为微软雅黑）

			四、font-style控制字体风格
				normal：默认
				italic：显示斜体的字体样式
				oblique:显示倾斜的字体样式

			五、font-weight 控制字体的粗细
				1.关键词: font-weight:  bold加粗/normal正常 
				2. 数字:   font-weight:  100-900; 
			400=normal
			700=bold
			六、font-variant规定小型大写字母的字体
				normal		默认值(正常显示)。
				small-caps	小型大写字母。
			七、字体复合样式：
				Font的基本形:font:font-size font-family   
				font:font-weight font-variant font-style（ font-size/line-height  font-family）

## 2. css控制文本
		
			一、text-align 控制文字水平方向位置
				1、left   水平距左  默认值
				2、center 水平距中
				3、right 水平距右

			二、line-height  文字在竖直方向距中显示
				line-height：25px;

			三、text-decoration  向文本添加修饰
				1、none	      默认。定义标准的文本。      
				2、underline            定义文本下的一条线。
				3、overline	      定义文本上的一条线。       
				 4、line-through       定义穿过文本的一条线。  

			四、text-indent 缩进文本
				1、em做单位 text-indent:2em;    1em代表一个汉字的距离
				2、px做单位 text-indent:20px     16px=1em;
				3、百分比  text-indent:200%;百分数要相对于缩进元素父元素的宽度。
				4、使用负值 text-indent:-2em；
			五、 text-overflow (css3)规定当文本溢出时处理方式；
				white-space:nowrap;
				clip:修剪文本
				ellipsis 	被修剪的文本用略符号来代表(....)。
				六.text-transform控制文本中的字母
				none:默认，定义带有大写字母和小写字母的标准的文本
				capitalize:文本中的每个单词以大写字母开头
				uppercase：定义仅有大写字母
				lowercase:定义仅有小写字母

			七、letter-spacing 字（字母）间距	letter-spacing:20px;

			八、word-spacing 词（单词）间距	word-spacing:20px;

			九、white-space  换行方式	
				normal 	默认
				nowrap 文本不会换行，文本会在在同一行上继续，
				直到遇到 <br> 标签为止。  
				十、word-break: 强制换行	normal 默认
				break-all 允许在单词内换行;

## 3. 特殊符号

			常用特殊符号:			
			所有特殊字符查看： 
			http://www.w3school.com.cn/tags/html_ref_symbols.html
