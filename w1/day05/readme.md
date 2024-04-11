# 1. CSS的定位
## 1. 属性 position定位
1. static 默认		在文档流中		不能移动
2. relative相对		在文档流中		能够移动，相对于原来的位置
3. absolute绝对		脱离文档流		能够移动，默认在原来的位置，使用偏移量相对于特殊定位的父元素【子绝父相】
4. fixed固定		脱离文档流		能够移动，默认在原来的位置，使用偏移量相对于窗口
## 2. 偏移量left、top、right、bottom
1. left、top 距某一侧的距离 left:50px;
2. right、bottom 如果元素靠右
## 3. z-index 堆叠次序

## 2. CSS的浮动
1. float 使元素脱离文档流 left|right
2. clear
3. 【拓展】浮动元素的特点？产生什么影响？如何解决？

## 3. CSS的显示
1. display 【重点】 消失|显示（块元素、行元素、行内块元素）
2. visibility 显示|隐藏（透明度为0） opacity:0;   0-1
3. overflow hidden