---
layout: post
title:  markdown语法
category: 读书
tags: markdown
description: 使用markdown提高写作效率，专注写作内容本身
---

### 特殊字符自动转换
- html中< 和 &需要做转换：
	1. < -> &lt;
	2. & -> &amp;
- markdown会自动转换

### 兼容html
* markdown 中插入html标签有效
* html区块标签中markdown无效
* html区段标签中markdown有效

---

### 区块元素

段落
 
- 有一个以上的文本行组成
- 前后有一个以上的空行分割


标题

* markdown支持类Setext 和类 atx形式
* 类Setext形式 = -
* 类Atx形式 #（1到6个）

区块引用

* \>行头插入，可以一行一个，也可以一段一个

列表

* 无序列表 
	+列项
	*列项
	-列项

* 有序列表
	1.列项

	数字+英文句点+列项的形式

代码块

	<code>codetext</code>

分割线

* 3个以上的\* \- \_

---

### 区段元素

强调

        * 强调文本 *	
    	_ 强调文本 _  
    	**强调文本**  
    	__强调文本__  	

如果想直接打印*或者_需要前面加\来转义

链接

	[链接文字]（链接url）



需要插\转义的符号

* \\
* \'
* \*
* \_
* \{}
* \[]
* \()
* \+
* \#
* \-
* \.
* \!

