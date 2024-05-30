# jQuery学习目标
1. 是什么？有什么用？怎么用？
2. 能够使用jQuery来获得网页元素
3. 能够使用jQuery代替JS事件处理，实现对节点的增删改查
4. 能够使用jQuery实现简单动画
5. 能够使用jQuery实现Ajax请求

# 1. jQuery概述
1. 是JS库  js文件
2. 有什么用？ 提高开发效率
3. 怎么用？ 
	1. 下载JS库，引入项目中（本地）
	2. 引入网络地址（网络CDN）
	
# 2. jQuery和JS操作DOM
## 1. 获得jQuery对象
1. 创建新对象（增）  $("<div></div>")  $(dom对象)
2. 已经存在对象 $("selector")
	1. CSS选择器
	2. jQuery选择器 位置$("selector:eq(n)") 状态$(":text") $(":disabled")
3. jQuery方法  obj.eq(index) obj.get(index)==obj[index]
4. 技能  jQuery对象和DOM对象互转
	 jQuery（j）-->DOM(d)  d= j[0]  d=j.get(0)
		DOM(d) --> jQuery（j）  j = $(d)     j = $($(d).get(0))  d= $(d)[0]

## 2. jQuery事件
1. $("button").click(fun)【重点】
2. 集合操作：自动对每一个元素进行操作
3. 链式语法：返回值依旧是jQuery对象，可以直接续写后续代码

4. $(document).ready()    onload
	onload:页面加载成功（所有资源加载完毕）之后触发   触发一次
	onready：节点加载完毕触发  可以触发多次
	
	$(document).ready(function(){})
	$().ready(function(){})
	$(function(){ 【重点】
		
	})
	
5. 事件绑定	
$("btn").bind("click",fun);【重点】   $("btn").on("click",fun);【重点：动态绑定】
$("btn").one("click",fun)
$("btn").unbind("click",fun);  $("btn").off("click",fun);
$("btn").unbind("click");
$("btn").unbind();  【重点】

## 3. 修改DOM元素
1. 获取/修改文本（普通文本/HTML文本）
	d.innerHTML      d.innerText    不赋值就是读，赋值就是更新（写）
	j.html()		j.text()		括号中不写内容就是读，括号中有内容就是更新
2. 修改属性
	d.getAttribute("A")  d.setAttribute("A","zhangsan")
	j.attr("A")			j.attr("A","zhangsan")  //适用于通用属性（包含自定义属性）
	Value既是一个属性，也提供了专门的方法
	d.value    d.value="654321"
	j.val()    j.val("654321")
	
3. 修改CSS
	d.getAttribute("style") d.setAttribute("style","color: red;")
	j.css("color")  j.css("color","red")
					j.css({"color":"red","font-size":"32px"})
	j.addClass("类名")  j.removeClass("类名")  j.toggleClass("类名")
	
## 4. 元素的增加和删除
1. 创建节点  $("<div></div>")  $(dom对象)
2. 添加到网页中