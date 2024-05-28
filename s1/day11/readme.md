# jQuery
1. 是什么？有什么用？怎么用？
2. 能够使用jQuery来代替JS实现事件响应
3. 能够使用jQuery来代替JS对网页元素进行增删改查
4. 能够使用jQuery实现简单动画
5. 能够使用jQuery实现Ajax请求

# 1. jQuery概述
1. 是什么？  JS库（封装了很多的方法）  *.js
2. 有什么用？ 提高开发效率
3. 怎么用？ 下载库到本地，引入网页；直接链接CDN地址

# 2. jQuery与JS
## 1. jQuery对象
1. 创建新对象    $("<div></div>")   $("<img src='*.jpg'/>")
2. 获取已经存在的对象[重点]  $("selector")
	1. 使用CSS选择器作为jQuery选择器--id选择器、class选择器....
	2. 使用jQuery位置选择器（可以根据位置找到需要的元素） $("selector:eq(n)")
	3. 使用jQuery筛选器（状态、控件类型筛选）
	4. 使用索引器获取指定对象 $("selector").eq(n) --- jquery
							$("selector").get(n) --- DOM
3. DOM（d）和jQuery(j)
	d-->j    j = $(d)
	j-->d	 d = j[0]  d=j.get(0)
	
## 2. jQuery事件
1. 语法 $("selector").事件名称(事件处理函数);
2. 语法风格：
	1. 链式语法
	2. jQuery集合（对集合直接进行操作，相当于对每个元素进行操作）
3. 事件名称没有on， 单击 click
4. 事件：ready     onload
	onload：资源加载完毕触发（外部资源）    只能写一次
		document.body.onload = function(){}
	onready：DOM树加载完毕触发（加载标签）  可以写很多次
	$(document).ready(function(){})
	$().ready(function(){})
	$(function(){})
5. 事件绑定
	bind  unbind one
	on（在元素生成期间绑定事件）  off

## 3. jQuery操作DOM（增删改查）
1. 查询
	使用jQuery选择器
2. 修改
	1. 修改文本  d.innerHTML    j.html("新的值")
	2. 修改纯文本d.innerText		j.text()
	3. 修改属性 d.setAttribute("属性","属性值") d.getAttribute("属性")
				j.attr("属性","属性值")   j.attr("属性")
	4. 修改值  d.value    j.val()
	5. 修改CSS  d.setAttribute("style","CSS样式")
			j.css("css样式","css样式值")
			j.css({CSS样式JSON})
			j.addClass()  j.removeClass() j.toggleClass();
	6. 如果修改单选、多选的状态，需要使用prop()
3. 增加
	1. 创建对象 $("<div></div>") 
	2. 将对象加入到网页中
4. 删除
	