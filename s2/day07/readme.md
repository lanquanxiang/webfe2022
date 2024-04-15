# 1. element对象的增删改查
## 1. 查询(6种)[重要*5，考试]
## 2. 修改[重要，考试]
1. 改变元素的文本 x.innerHTML(识别并执行HTML代码) x.innerText（纯文本）
2. 改变元素的值（全局属性）value（计算器）、id、class、style（样式）、title  x.style.color="red";
3. 改变元素的属性 
	1. 增加属性 Element.setAttribute("attr",val)   x.setAttribute("style","color:red;") 
	2. 删除属性 Element.removeAttribute()
	3. 修改属性值 Element.setAttribute("attr",val)
	4. 得到属性 Element.getAttribute("attr") x.getAttribute("value")

# 2. 数组
1. 数组的初始化  var array1 = [];
2. 数组的常用属性和方法 
	1. 数组的长度
	2. 数组的拼接、头部增加和删除、尾部增加和删除
	3. 数组的排序和逆序
	4. 数组转换为字符串 toLocalString() join(char)

# 3. 字符串
1. 初始化
	string和String的区别？
2. 属性和方法
	1. 长度
	2. 字符的定位（index -- char）
	3. 字符串的截取
	4. 将字符串转为数组 split(char)
3. 对象
	1. 对象的初始化 {}
	2. obj.attr = val;
	3. delete obj.attr

# 4. Math
1. 常用方法

# 5. 日期Date
1. 初始化
2. 常用方法
3. 获取日期数据