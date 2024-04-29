# 1. 事件处理
1. 事件源
2. 事件
3. 事件处理程序
# 2. 事件处理程序调用
1. 直接在HTML标签中调用（注意调用多个函数的写法）<button onclick = "fun1(),fun2()"></button>
2. 获取元素，为元素的事件属性赋值一个函数 ele.onclick = fun1;ele.onclick = fun2; var fun1=function(){}
3. 获取元素，为元素添加事件监听
4. 上述三种方法的优缺点？
# 3. 事件模型
1. 事件传播顺序（根节点---子节点---根节点）
2. 捕获阶段（根→子） 目标节点（子节点触发事件） 冒泡节点（子→根）
# 4. 事件对象【重要】
1. event
2. event.target事件源
3. event.currentTarget
4. event.type事件类型
# 5. 常用事件【重点】
1. 鼠标事件 click dblclick mouseenter、mouseover  mouseout
2. 键盘事件 keypress
3. 表单事件【重点】
	1. change
	2. blur
	3. submit
4. 窗口 load 页面加载完毕之后触发（加载后续的网页元素防止元素还没有渲染、自动运行脚本）
扩展：如何阻止事件的默认行为
1. event.preventDefault()
2. 事件处理程序返回false

扩展：重点：表单验证
1. 非空  \S{1,}
2. 长度 length .{}
3. 数字 isNaN  \d
4. 正则表达式