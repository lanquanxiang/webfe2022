# 1. 正则表达式【必须】
## 1. 初始化
1. var reg = /pattern/flags;
2. var reg = new RegExp("pattern", "flags");
## 2. 表达式
1. 类别（字母、数字、任意字符）
2. 组合（x|y  [xyz]）
3. 量词 （* + ？ {}）
4. 定位符（开始、结束）
## 3. 使用
reg.test(str)


# 2. DOM(增删改查)
## 1. 节点的创建和增加
1. createElement
2. innerHTML修改文本
3. setAttribute 修改属性
4. appendChild追加节点
## 2. 批量增加节点
1. 创建碎片
2. 向碎片追加内容
3. 将碎片追加到文档
## 3. 节点的删除
1. 父节点x.parentNode才能删除子节点x
2. removeChild
## 4. (了解)节点克隆和替换

# 3. BOM
## 1. 重要的属性
1. location.href 网页跳转
## 2. 重要的方法
1. w = open(url,name,窗口特征-宽高位置)
2. w.close()
## 3. 交互框
1. alert
2. confirm
3. prompt
## 4. 计时器
1. setTimeOut(fun,time) fun函数名字，time毫秒
2. setInterval(fun,time) fun函数名字，time毫秒
3. 清除 clearTimeOut  clearInterval
4. 【面试】计时器的执行顺序
	JS的执行机制
