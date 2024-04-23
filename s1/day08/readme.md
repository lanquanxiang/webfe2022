# 1. RegExp
1. 如何初始化？ var reg = /pattern/;
2. 如何编写正则表达式（类别词、量词、边界符） /^\d{11}$/
3. 如何使用？reg.test(str)

# 2. DOM
## 1. DOM树的结构
1. 文档节点、元素节点（文本节点、属性节点）
2. 常用属性parentNode  childNodes
## 2. DOM树节点
1. 增加
	1. 创建元素
	2. 修改文本/添加属性
	3. 将元素添加到文档中
扩展：批量增加
2. 删除
	removeChild()
	
# 3. BOM
1. 做什么？控制浏览器：窗口打开/关闭、历史记录、前进和后退
## 1. window属性
1. document
2. location
## 2. window重要方法
1. 打开和关闭窗口
## 3. 交互框
1. alert 警告
2. confirm 确认
3. prompt 询问
## 4. 定时器
1. 一次
2. 周期性
3. 清除定时器