# 1. Element元素 HTML
## 1. 查询（重要，考试必考）
1. 6种方法（五颗星）
![](readme_files/1.jpg)
## 2. 修改
1. 文本 innerHTML  innerText（重要）
	1. 得到文本
	2. 修改文本
2. 属性（全局id/class/title/style/ input--value、一般属性）
	1. 值  x.value  x.id  x.class  x.style.color="red"
		扩展：计算器
			1. 字符串--> 数字  Number() 减0  parseInt parseFloat
			2. 0.1+0.2!=0.3
			3. 除数不能为0
			4. 输入内容不是数字？
	2. 属性（一般） 特别地，如果修改的属性是style，可以来控制CSS
		1. 增 x.setAttribute("属性名","属性值")
		2. 删 x.removeAttribute("属性名")
		3. 改 x.setAttribute("属性名","属性值")
		4. 查 x.getAttribute("属性名")
## 3. 增加（DOM）
## 4. 删除（DOM）

# 2. 数组
1. 数组如何初始化？ var a=[]
2. 常用属性？ length   如果长度设置为0，表示清空数组
3. 常用方法
	1. 数组元素连接
	2. 数组元素增删（头部、尾部）
	3. 数组元素排序和逆序
	4. 数组-->字符串 join()  toLocalString()