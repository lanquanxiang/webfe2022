# 1. 超链接
1. 标记与常用属性【重点】  <a href="超链接目标URI" [target=""] [name=""]>超链接内容</a>
2. 文本链接（新窗口打开）
3. 书签链接（网页内容很多，方便用户查看）
	1. 方法一：在目标位置使用name来定义锚点； <a name="top"></a>
	2. 方法二：在目标位置为某个元素附加id，使用这个元素作为锚点； <div id="bottom">这是网页内容</div>
	3. 链接到书签 <a href="#书签名/锚点名">超链接内容</a>
4. 空白链接（开发的时候常使用）【掌握】三种空白链接，区别
5. 图像链接  a>img
6. email链接：了解

# 2. 表格
1. 作用：展示信息；排版
2. 组成（标记）【重要】  table>(caption + (tr>td|th) )
3. 表格单元格合并【重点】
4. 结构标记（方便多行处理）thead tbody tfoot (了解)
5. 属性：align 水平 v-align 垂直 top bottom middle 背景色 bgcolor  背景图 background

# 3. 【考试，重点】表单
1. 作用：收集用户数据
2. 表单标记和属性
```
<form action="" method="" enctype="" name="">
  <!--表单控件-->
</form>
```
 扩展：get和post的区别【考试，面试】
3. input控件【考试，重点，编程题第一题10分】
	``` <input type="" [name=""] [value=""] [id=""]/> ```
	10种input类型：4个框 4个按钮 2个域
