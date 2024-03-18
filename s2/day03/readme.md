# 1. CSS基础知识
1. CSS是什么？有什么作用？有什么特性？
2. 【重点】CSS的声明编写规则。 selector { property1:value1; property2:value2;……}
3. CSS的使用（四种）
	1. 外链【开发】：在css文件中编写，然后link链接到网页中
	2. 导入：在css文件中编写，然后在style使用import导入
	3. 内部【常用】：在html中编写，在style中书写样式
	4. 行内：在html的标签中使用style属性写

# 2. CSS选择器
1. 常用选择器【掌握】
	1. *通配符 默认样式，清除样式
	2. 元素选择器（标记选择器/标签选择器/类型选择器） 
	3. id选择器
	4. class选择器
2. 组合选择器
	1. 后代 E F   div>span>img
	2. 父子 E>F
	3. 相邻兄弟选择器 E+F  div+span+img
	4. 通用/普通兄弟选择器 E~F 
	5. 同时声明 E,F
3. 属性选择器
	1. 存在attr属性  E[attr]
	2. 存在attr属性，且值等于val  E[attr=val]
	3. 存在attr属性，且值以a开头  E[attr^=a]
	4. 存在attr属性，且值以b结尾  E[attr$=b]
	5. 存在attr属性，且值包含c    E[attr*=c]
4. 伪元素选择器
	1. before
	2. after
5. 链接伪类选择器
	1. hover
	2. focus
6. 状态伪类选择器
	1. empty
	2. disabled
7. 结构伪类选择器
	1. nth-child
	2. first-child
# 3. 选择器优先级
	1. important > 行内样式 > 外部样式|内部样式
	2. id选择器 > class选择器 | 属性选择器 | 伪类选择器 > 元素选择器| 伪元素选择器 > 通配符选择器