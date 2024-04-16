# 1. JavaScript的概述
1. JavaScript是什么？	脚本语言|浏览器解释执行
2. JavaScript的特点？	解释性、弱类型、基于原型
3. JavaScript的作用？	通过事件响应控制HTML和CSS
4. JavaScript的语法特点？

# 2. JavaScript的使用
## 1. 创建
1. 行内式：事件中、超链接中（建议1-2行）
2. 内嵌式：```<script></script>```
3. 外链式:``<script src="url"></script>```
## 2. 使用
1. 输出到控制台 console.log()
2. 输出到网页

# 3. 变量及声明
## 1. 变量的声明
1. var（全局）-- 变量可以直接使用不声明  变量提升（只提升声明）
2. let
3. const
## 2. 变量的类型
1. boolean
2. null
3. undefined
4. 数字
	1. 整数 八进制和十六进制的定义
	2. 小数 .1==0.1  0.1+0.2！=0.3
	3. 特殊值 Infinity 什么时候出现无穷大/小？如何判断？isFinite()
	4. 特殊值 NaN  什么时候出现NaN？如何判断？isNaN()
5. 字符串 单引号或双引号定义，如果串中带有引号，可以嵌套或者转义
## 3. 运算符
1. 加法 如果操作数一端是字符串，视为字符串拼接，技巧：+""
2. 减法 将两个操作数转换为数字，技巧：使用-0来将类型转为数字
3. == (值)和 ===（值+类型）
## 4. 类型转换
1. 将类型转为数字
	1. 减0 无法转换NaN
	2. Number() undefined|{}--NaN  null|[]--0
	3. parseInt  parseFloat 解析
2. 将类型转为字符串
	1. +""
	2. x.toString() 不适用于null/undefined
	3. String()
3. 将类型转为boolean（条件判断）
	1. Boolean()
	2. 0、-0、null、false、NaN、undefined、""

# 4. 函数及使用【重点】
## 1. 函数的声明
function是一个函数，还是一个变量，还是一个对象。
1. function关键字  function xxx(){}
2. var、let来声明函数变量 var xxx = function(){}
3. 使用Function()构造方法来构造
## 2. 函数的调用
1. 立即执行函数表达式()
2. 通过函数名称直接调用（注意没有重载，参数个数不一致）
3. 通过事件调用
4. 通过超链接调用

# 5. 常用对象
## 1. element元素--html元素【重点，考试】
1. 查询【考试】 6种
2. 修改
	1. 修改文本 innerHTML（识别和执行html代码）/innerText（纯文本）属性
	2. 修改属性
		1. 修改全局属性
		2. 修改其他属性