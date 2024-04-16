# 1. element元素
## 1. element元素操作【重点，考试】
1. 查询【考试】 6种
2. 修改
	1. 修改文本 innerHTML（识别和执行html代码）/innerText（纯文本）属性
	2. 修改属性
		1. 修改全局属性 element.id、class、element.value、element.style.color="red"
		2. 修改其他属性
			1. 增加属性  setAttribute(attrName, value)
			2. 修改属性  setAttribute(attrName, value)
			3. 删除属性  removeAttribute(attrName)
			4. 获得属性  getAttribute(attrName)
3. 增加元素（节点）DOM树
4. 删除元素（节点）DOM树

## 2. 扩展
1. 如何判断输入的内容是数字？ isNaN
2. 如何将字符串转换为数字？ -0
3. 注意除数不能为0  1/0 infinity
4. 注意浮点数运算问题0.1+0.2=？ 解决？ 精确到小数点后15位

# 2. 数组
## 1. 数组的初始化
var x=[];
## 2. 数组的常用属性和方法
1. 长度
2. 拼接
3. 操作元素（头部增加和删除、尾部增加和删除）
4. 操作数组（排序、倒置）
5. 输出（toLocalString() join("...")）
6. 扩展：如何清空数组？ x=[] x.length = 0;

# 3. 字符串
## 1. 字符串
1. 字符串的初始化 string和String的区别
2. 字符串的属性和方法
	1. 长度
	2. 字符--索引的相关方法
	3. 字符串截取（开始-结束，开始-长度）
	4. split -- join
## 2. 自定义对象
1. 初始化 var obj={}
2. 对象的属性（增删改查）

# 4. Math
1. 常量 PI
2. 方法
	1. 三角函数
	2. 数据处理 （向上、向下、四舍五入）
	3. 随机函数