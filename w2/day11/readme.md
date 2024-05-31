# jQuery目标
1. 【了解】jQuery是什么？有什么用？怎么用？
2. 【重点】能够使用jQuery来代替JS进行事件响应
3. 【重点】能够使用jQuery来代替JS进行节点增删改查
4. 【了解】能够使用jQuery来实现简单动画
5. 【了解】能够使用jQuery来实现Ajax

# 1. jQuery概述
1. 是什么？ js库  *.js文件
2. 有什么用？ 提高开发效率
3. 怎么用？
	1. 官网下载，引入到项目中
	2. 引用网络地址

# 2. jQuery代替JS（DOM操作）
## 1. jQuery对象
1. 创建新的对象 $("<div></div>")   $("<a></a>") $("<img/>")
2. 获得已经存在的对象 $("selector")
	1. CSS选择器
	2. 位置选择器 $("selector:eq(n)")
	3. 筛选选择器
3. jQuery常用方法
	1. obj.eq(index)
	2. obj.get(index)   obj[index]
4. DOM对象（d）和jQuery对象(j)互转
	d = j.get(0)  d = j[0]
	j = $(d)      j = $($(j[0]).get(0))
	
	$(j[0].parentNode)
	
## 2. jQuery事件处理
1. 事件响应 $("button").click(fun)
2. 事件绑定和解绑
	$("button").bind("click",fun)
	$("button").one("click",fun)  //一次性事件
	$("button").unbind("click",fun) //解除fun绑定
	$("button").unbind("click") //解除单击的所有函数
	$("button").unbind() //解除所有事件
3. 【扩展】jQuery模拟操作
4. 语法：
	1. 链式语法
	2. 对jQuery集合进行操作，默认对集合中的每一个元素进行操作
5. 特殊事件 ready		onload
	onload：网页资源（外部资源）加载完毕之后触发 只触发一次
	onready：文档节点加载完毕就触发  可以触发多次【推荐】
	$(document).ready(function(){  /*网页加载完毕之后执行的代码*/  })
	$().ready(function(){  /*网页加载完毕之后执行的代码*/  })
	$(function(){
		/*网页加载完毕之后执行的代码*/
	})
	
## 3. 节点操作
1. 查询
2. 修改
	1. 修改文本（纯文本、HTML文本）
		d.innerText    d.innerHTML
		j.text()		d.html()  括号中没有内容，获取；括号中有内容，设置
	2. 修改属性
		d.getAttribute("id") 	d.setAttribute("id","lisi")
		j.attr("id")			j.attr("id","lisi")
		
		d.value
		j.val() 括号中没有内容，获取；括号中有内容，设置
		
	3. 修改样式
		d.setAttribute("style","color:red;")
		j.css("color","red")   j.css("color")
		j.css({"color":"red","font-szie":"32px"})
		
		j.addClass("类名")   j.removeClass("类名")  j.toggleClass("类名")
3. 增加和删除
	1. 创建一个节点 创建新的对象 $("<div></div>")   $("<a></a>") $("<img/>")
	2. 将节点加入网页中
	3. 删除（获得节点）