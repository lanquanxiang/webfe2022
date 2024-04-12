# 1. CSS的定位
## 1. position定位方式
1. static	默认		在文档流中	无法移动，无法堆叠
2. relative 相对		在文档流中	可以移动，相对于原来的位置，不能堆叠	
3. absolute 绝对		脱离文档流	可以移动，默认在原来的位置，偏移时相对于特殊定位的父元素【子绝父相】
4. fixed	固定		脱离文档里	可以移动，默认在原来的位置，偏移时相对于窗口【不随鼠标滚动】
## 2. 偏移量
1. left   可以是固定值140px，百分比 50%
2. top
3. right
4. bottom
## 3. z-index堆叠
1. 取值：数值 越大越上层
2. 只有absolute、fixed

# 2. CSS的浮动
1. float:left|right;
2. 浮动元素的特点？【掌握】
	1. 脱离文档流
	2. 行内块元素
	3. 尽可能向左|右，直到边框或其他浮动元素
	4. 尽可能向上，直到边框或块元素的底部
3. 【面试】浮动元素可能产生什么影响？如何消除浮动？ clearfix

# 3.CSS的显示
## 1. overflow 溢出
1. hidden [掌握]
## 2. visibility 可见的
1. hidden：元素不可见（元素的透明度为0 opacity:0）仍在在文档中
## 3. display显示【重要，考试】
1. 显示 block(块元素) inline（行元素） inline-block（行内块元素） table
2. 消失 none 从文档中消失

# 4.CSS3常用新特性【重要，了解】
## 1. 圆角
 border-radius:长度，百分比 可以用1~4个来设置四个角的弧度
## 2. 图像边框
border-image：图像地址 30 30 30 30
## 3. 盒子阴影
## 4. 滤镜
## 5. 变形与动画
1. 变形：transform 移动、旋转、缩放
2. 动画：animate

