# jQuery
1. 能够在页面中引入jQuery，使用jQuery进行开发
2. 能够使用jQuery来替换事件响应
3. 能够使用jQuery来替换对象操作（节点的增删改【文本、属性、样式】查）
4. 能够使用jQuery来实现简单动画
5. 能够使用jQuery来实现Ajax操作

# 1. jQuery概述
1. 是什么？ JS库 *.js
2. 有什么用？ 写得更少，做得更多
3. 怎么用？[1.下载到本地，链接到项目中 2. 直接链接主流CDN地址]

# 2. jQuery与 JS【重点】
## 1. jQuery对象
1. 直接传入标签对  创建元素
2. 参数：CSS选择器【重点】 获取元素
3. 可能获得多个对象  $("selector:eq(index)")
4. 可能获得多个对象  $("selector").eq(index)  jquery
					$("selector").get(index) DOM
5. jQuery对象A和JS互转B
	A-->B   A[0]  A.get(0)
	B-->A   $(B)

## 2. jQuery事件
1. 事件响应  $("selector").click(事件响应函数)
2. 特殊事件 $("selector").ready(事件响应函数)  onload
	$("document").ready(事件响应函数)
	$().ready(事件响应函数)
	$(事件响应函数)
	$(function(){
		
	})
3. 事件绑定
	btn.addEventListener("click",function(){},false)  btn.removeEventListener("click",function(){},false)
	btn_jquery.bind("click",function(){})			btn_jquery.unbind("click")
	btn_jquery.on("click",function(){})				btn_jquery.off("click")
	btn_jquery.one("click",function(){})	

4. 修改元素
	1. 修改html文本 ele.innerHTML   ele.html()  如果函数的括号中没有值，表示获取
	2. 修改纯文本   ele.innerText	ele.text() 如果函数的括号中有值，表示设置
	3. 修改属性 ele.get/setAttribute()	ele.attr()
	4. 修改value  ele.value		ele.val()
	5. 修改CSS ele.get/setAttribute("style","CSS样式表") ele.attr("style","CSS样式表")
		addClass  removeClass  ele.css()



