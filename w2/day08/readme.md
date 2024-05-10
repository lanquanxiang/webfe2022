# 1. 常用对象：正则表达式
1. 如何初始化正则？ var reg = /^pattern$/
2. 如何编写正则？
	1. 类别词 \d \w [0-9] [A-z]
	2. 量词 * + ? {}
	3. 组合符 x|y  ()
	4. 边界符 ^ $
3. 如何使用正则来校验数据？
	1. reg.test(xxxx)

# 2. DOM文档对象模型（document）
1. 能够复述有哪些节点？  文档节点（元素节点（文本节点+属性节点）+ 注释节点）
2. 能够复述节点的构成？ parentNode  childNodes  nodeType  nodeValue
3. 能够对节点进行增删【改查】？
	1. 对节点进行增加
	2. 批量增加
	3. 删除节点
	4. 节点的克隆、节点替换（了解）

# 3. BOM浏览器对象模型（window）
1. window.location.href（定位URL）
2. window.document
3. window.document.cookie【掌握，不考，保存用户信息】
4. 窗口方法： open close
5. 交互框：alert警告 confirm确认（boolean） prompt询问框（string null）
6. 计时器（异步执行）
	1. setTimeout(fun,time)
	2. setInterval(fun,time)
	3. 学会清除计时器
	4. 【面试】JS执行机制