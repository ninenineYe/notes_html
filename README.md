# notes_html
这是学习html基础的概念和笔记
html语法规范
<html></html>
<br />
大部分标签都是成对存在的
标签关系：包含关系和并列关系
包含关系如下
<head>
	<title> </title>
</head>
并列关系如下
<head></head>
<body></body>
骨架标签，即基本的结构标签
<html>根标签,html标签
头部标签<head>
<title>标题标签
<body>主体标签
shift+alt+下箭头：快速复制粘贴上一行
双击文本+ctrl+d：选中相同文本
ctrl+h：可全局替换
ctrl+g：跳转具体行数
shift+alt：选中语句区块
<!DOCTYPE>文档类型声明标签<!DOCTYPE html>表示用html5版本显示网页,需要位于文档最前面.
lang语言种类，用来显示当前文档显示的语言，en定义为英语网页，zh-CN是中文网页
<meta charset = "UTF-8">存储用万国码存储，防止乱码
<p></p>段落标签
<br/>换行标签,且是单标签，其跟段落标签的区别是：段落标签使用之后段落与段落之间有一个较大的缝隙，而换行标签只是另起一行，并不分段。
文本格式化标签：加粗、斜体、下划线等
加粗：<strong></strong>、<b></b>
倾斜：<em></em>、<i></i>
删除线：<del></del>、<s></s>
下划线：<ins></ins><u></u>
<div></div> <span></span>：是没有语义的，是一个盒子，用来装内容
<div></div>：单独占一行的大盒子
<span></span>：意为分区、跨距，一行可以放多个<span>盒子
<img>:单标签，用于定义图像
如：<img src ="图像URL"/>,src是必须属性，用于指定图像文件的路径和文件名
alt：用于图片显示不出来的时候用文字替换图像
如：<img src ="ssss.jpg" alt="我是你爹"/>
title:提示文本，鼠标放到图像上，提示文字
如：<img src ="ssss.jpg" alt="我是你爹" title="我是帅气大男孩"/>
width:图像宽度
如：<img src ="ssss.jpg" alt="我是你爹" title="我是帅气大男孩" width="500"/>
height:图像高度
如：<img src ="ssss.jpg" alt="我是你爹" title="我是帅气大男孩" height="500"/>
border:给图像设定边框
图像之间的属性没有先后顺序，属性和属性之间均已空格分开，标签名和属性已空格分开
属性采取键值对的格式，即key=“value”
目录，根目录
相对路径，绝对路径
相对路径同一级、上一级、下一级路径引用
上一级相对路径../
绝对路径：电脑中的位置地址
绝对路径用\\
相对路径用//
<a>超链接标签
语法格式：<a href ="跳转目标" target="目标窗口的弹出方式">文本或图像</a>
a的意思是anchor
href指定链接目标地址
链接分类：外部链接，内部链接
target指定链接目标打开方式，_self为默认值，_blank为在新窗口（新标签页）中打开方式
href 后面的值是 http：// +新标签页地址  的形式（此方式为外部链接）
href 后面不需要http时是内部各标签页的链接，即是内部链接
空链接 <a href ="#"></a>
下载链接：如果href里面地址是一个文件或者压缩包，会下载这个文件
下载链接：<a href=></a>
网页元素链接
锚点链接点击链接，可以快速定位页面中的某个位置
在链接文本的href属性中，设置属性值为#名字的形式，如<a href=“#two”>第二集</a>
目标位置标签，添加id属性=刚才的名字，如：<h3 id="two"></h3>
注释标签<！-- -->
特殊字符：空格&nbsp;小于号&lt;大于号&gt;和号&amp
  表格标签
表格标签主要用来展示数据
<table>
<tr>
<td>单元格内文字</td>
</tr>
</table>
<table></table>表示表格生成
<tr></tr>表示行
<td></td>表示单元格
表头单元格<th></th>表头单元格里面的文本内容加粗居中显示(table head)
表格属性一般用css设置，但是html也有表格属性的开发
表格属性写在table里面
align：规定表格周围元素的对齐方式
属性值：left，right，center
border：规定表格单元是否拥有边框，默认为“”，表示没有边框
属性值：1或者“”
cellpadding：规定单元边沿与其内容之间的空白，默认一像素
属性值：像素值
cellspacing：规定单元格之间的空白，默认两像素
属性值：像素值
width：规定表格的宽度
属性值：像素值或者百分比
表格结构标签
<thead>表示表格的头部区域
<tbody>表示表格的主体区域
  <tr>要放在<thead>内部
合并单元格
合并单元格的方式：
跨行合并（rowspan）
跨列合并（colspan）
跨行合并时目标单元格为最上侧单元格
跨列合并时目标单元格为最左侧单元格
列表标签
列表是用来布局的
<input>表单元素。type属性，如type=“text”等
name属性定义input的名称，value定义input的值，checked规定此input元素首次加载时应当被选中，maxlength规定输入字段中的字符的最大长度，属性值应为正整数。
radio单选框；checkbox复选框；password密码框
