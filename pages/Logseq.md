- 非常棒的 [[笔记软件]]
- # 待办事项todo
	- DONE 阅读[[《为什么时间不够用》]]
	  :LOGBOOK:
	  CLOCK: [2022-03-19 Sat 20:51:53]--[2022-03-19 Sat 20:51:59] =>  00:00:06
	  :END:
	- TODO 去运动
	  DEADLINE: <2022-03-20 Sun 20:54>
	- CANCELED 和同事吃饭
	- WAITING 背单词
	- DONE 去快递
	  :LOGBOOK:
	  CLOCK: [2022-03-19 Sat 20:54:06]--[2022-03-19 Sat 20:54:11] =>  00:00:05
	  :END:
	- DOING [#B] logseq进阶
	  :LOGBOOK:
	  CLOCK: [2022-03-19 Sat 21:01:23]
	  :END:
	- TODO 每天复盘
	  SCHEDULED: <2022-03-20 Sun .+1d>
	  :LOGBOOK:
	  CLOCK: [2022-03-19 Sat 20:59:38]--[2022-03-19 Sat 20:59:39] =>  00:00:01
	  CLOCK: [2022-03-19 Sat 20:59:41]--[2022-03-19 Sat 20:59:42] =>  00:00:01
	  * State "DONE" from "TODO" [2022-03-19 Sat 20:59]
	  :END:
	- > 好的todolist:  状态， 优先级， 标签， 页面引用， emoji表情以及日期引用
	- [#C] TODO #事务工作 提交工作报告 [[xxx的工作报告]]
	-
- # markdown语法
	- ## 嵌套引用
		- > 一级引用
		  >> 二级引用
		  >>> 三级引用
	- ## 上标 下标 下划线
		- 文字 <sup>上标文字</sup>
		- 文字 <sub>下标文字</sub>
		- 下划线 <u>下划线文字</u>
	- ## 转义字符
		- \**文字
- # 尖括号命令
	- #+BEGIN_NOTE
	  这是一条笔记
	  #+END_NOTE
	- #+BEGIN_TIP
	  这是一条提醒
	  #+END_TIP
	- #+BEGIN_IMPORTANT
	  重要的信息
	  #+END_IMPORTANT
	- #+BEGIN_PINNED
	  图钉
	  #+END_PINNED
	- #+BEGIN_WARNING
	  警告信息
	  #+END_WARNING
	- #+BEGIN_QUOTE
	  引用
	  #+END_QUOTE
	- #+BEGIN_CENTER
	  中间的文字
	  #+END_CENTER
- # 数字公式
	- 行内公式 $a=b$
	- 跨行公式
	  $$a=b$$
	- 上标
		- $$a^2$$
		- $$a^{2x+y}$$
	- 下标
		- $$a_2$$
		- $$a_{2x+y}$$
	- 根号
		- $$\sqrt{x}$$
		- n次方根
		  $$\sqrt[n]x$$
		-
	- 单个字符向量
		- $$\vec{ab}$$
		-
- # 文字格式
	- ## 语法一
		- ```html
		  <p style="关键词:值">输入文字</p>
		  ```
		- ### 字体
			- 关键词： font-famliy; 值： 字体名称
			- 示例：
				- <p style="font-family:宋体">字体为宋体</p>
				- <p style="font-family:隶变">字体为隶变</p>
				- <p style="font-family:娃娃体">字体为娃娃体</p>
				- <p style="font-family: 华文细黑">字体为华文细黑</p>
				- <p style="font-family:宋体">字体为宋体</p>
				  <p style="font-family:微软雅黑">字体为微软雅黑</p>
				  <p style="font-family:方正喵呜体">字体为方正喵呜体</p>
		- ### 字号
			- 关键词：font-size；值：正数+px
			- <p style="font-size:3px">字号为3px</p>
			  <p style="font-size:5px">字号为5px</p>
			  <p style="font-size:10px">字号为10px</p>
			  <p style="font-size:15px">字号为15px</p>
			  <p style="font-size:20px">字号为20px</p>
		- ### 颜色
			- 关键词：color；值：颜色代码 或 颜色英文
			- <p style="color:red">红色字体</p>
			  <p style="color:blue">蓝色字体</p>
			  <p style="color:#009100">#009100色字体</p>
			  <p style="color:#CA8EFF">#CA8EFF色字体</p>
			  <p style="color:#408080">#408080色字体</p>
			-
-
-