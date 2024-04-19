# 1. JS概述
## 1. 概念
1. 什么是JS？ 脚本语言（浏览器解释执行）
2. JS有什么特点？ 动态、弱类型、基于原型（面试）、解释性
3. JS有什么作用？ 交互--控制HTML和CSS（DOM）--控制浏览器BOM（打开关闭窗口、前进后退、历史记录）
4. JS的构成（ECMAScript、DOM、BOM）
5. JS语言特点？
## 2. JS的创建及使用
1. 行内脚本
	1. 事件响应 onclick
	2. 超链接 href="javascript:"
2. 内部脚本  ```<script type="text/javascript">脚本代码</script>```
3. 外部脚本  ```<script type="text/javascript" src="地址"></script>```
## 3. 测试使用
1. alert(1)
2. console.log(1)
3. document.write()

# 2. JS基础语法
## 1. 变量声明
1. var（全局）
2. let ES6（作用域）
3. const 常量（必须初始化）
4. 变量提升（面试）
## 2. JS的数据类型（8种）
1. boolean
2. null（需要返回对象的时候，学号-->学生 public class Stu{}   public Stu getStuBySno(String sno)）
3. undefined 未初始化 var x;  var x=[1]; x[2]==undefined   null==undefined
4. number数值
	1. 整数 0--八进制（不建议） 0x--十六进制
	2. 浮点数（小数） .1 == 0.1    面试： 0.1+0.2!=0.3 为什么（小数不能精确表示）？解决（保留小数点后16位）toFixed(16)？
			整数--二进制（除二取余） 小数--二进制（乘二取整）
	3. Infinity 无穷大 isFinite()
	4. NaN  isNaN(x)   NaN
5. (了解)BigInt
6. (了解)Symbol 不重复的唯一值
7. string 字符串 单引号/双引号  如果字符串中有特殊字符（单双引号）--嵌套/转义
8. Object 对象
## 3. 运算符和优先级
1. 加法+ 如果有一端是字符串，字符串拼接
2. 减法- 将两端转为数字
3. 相等== （值）  全等于===（值+类型）

# 3. 函数的定义和使用（重要）
## 1. 函数的定义（函数、变量、对象）
1. function声明函数（掌握）
2. var 声明函数变量（掌握）
3. new 构造函数对象（了解）
扩展：与Java函数的区别
	1. 返回值由主体中return关键字决定
	2. 形参列表中不需要var
	3. 没有函数重载
	4. 参数个数可以不相同，参数多了就丢弃，参数少了，参数值undefined
## 2. 函数的调用
1. 立即执行函数 (function(){})();
2. 使用函数名直接调用 add(1,2,3);
3. 使用事件响应调用
4. 使用超链接调用

# 4. Element元素 HTML
## 1. 查询（重要，考试必考）
1. 6种方法（五颗星）
## 2. 修改
1. 文本 innerHTML  innerText（重要）
	1. 得到文本
	2. 修改文本
2. 属性（全局id/class/title/style/ input--value、一般属性）
	1. 值  value
## 3. 增加（DOM）
## 4. 删除（DOM）