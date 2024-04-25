# 1. element 元素
## 1. 查询
## 2. 修改
1. 修改文本
2. 修改属性 ele.value ele.id `ele.style.width=100px;`
	1. 增加 ele.setAttribute("attrname","值")	
	2. 删除 ele.removeAttribute("attrname")
	3. 修改 ele.setAttribute("attrname","值")  ele.setAttribute("style","width: 100px;")
	4. 获得 ele.getAttribute("attrname")
## 3. 增加 DOM
## 4. 删除 DOM

# 2. 数组Array
1. 初始化？ var a=[];
2. 常用属性 a.length
3. 常用方法
	1. 数组连接
	2. 数组元素操作（头部增删、尾部增删）
	3. 排序和逆序
	4. 数组转字符串（join、toLocalString）

# 3. 字符串String
1. string和String的区别？
2. 常用属性 length
3. 常用方法
	1. index--char
	2. 字符串截取（开始，结束|长度）
	3. 字符串分割为数组
扩展：自定义对象 
1. 初始化 var obj = {}
2. 为自定义对象添加属性和属性值  obj.属性 = 属性值   obj["属性"]=属性值
3. 访问属性和属性值  obj.属性

# 4. Math
1. 常量  PI
2. 三角函数
3. 数字操作（四舍五入、向上向下取整、绝对值）
4. 随机数[0,1) [0,n]  [m,n]

# 5. Date
1. 如何初始化日期（当前日期/指定日期）
2. 如何获取日期中的年月日时分秒
3. 如何获得时间戳？