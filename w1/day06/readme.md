# 1. 概述
## 1. 基础知识
1. JS是什么（脚本语言）？有什么特点？（理解）
2. JS的作用？（交互--对网页、浏览器进行操作） 事件响应（重点，考试）
3. JS的组成（ECMAScript、DOM（重点，考点）、BOM）
## 2. JS的创建和使用
1. 行内（事件响应+超链接）
2. 内部（多段脚本，从上到下）
3. 外部（Script src）

# 2. 语法
## 1. 变量的声明
1. var
2. let
3. const
4. 变量提升（面试）：var 提升声明，不提升赋值
## 2. 变量类型
1. boolean
2. null
3. undefined 未初始化  null==undefined
4. number
	1. 整数  010等于八进制的8
	2. 浮动书 .1相当于0.1  0.1+0.2!=0.3 原因？小数无法精确表示。怎么解决？修改精确度 tofixed(16)
	3. Infinity
	4. NaN  isNaN()判断是否是非数字
5. string
	1. 单引号和双引号
	2. 注意单双引号嵌套使用 "  \'  " " ' "
	3. 可以直接使用转义字符
## 3. 运算符
1. +：如果一端是字符串，另外一端转为字符串，字符串拼接
2. -：将两端转为数字
3. ==（面试）

# 3. 函数function
1. 变量
2. 函数
3. 对象
## 函数的定义和使用
1. 定义： function xx(){}、var xx = function(){}、 var xx = new Function("","主体")
2. 使用：(function(){})();  xx();  事件响应onclick 超链接点击调用

# 4. Element(HTML元素)【重点，考试】
## 1. 查【重点，五个星】 6种方法
## 2. 修改
	1. 文本 innerHTML  innerText
	2. 属性(全局属性 id、class、style（不建议）、表单控件value、一般属性)
## 3. 增加（DOM）
## 4. 删除（DOM）

