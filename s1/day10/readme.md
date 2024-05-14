# Ajax目标
1. 能够复述Ajax是什么？由哪些技术构成？有作用？有优缺点？
2. 能够使用Ajax发起同步/异步请求，请求txt数据
3. 能够编写XML文件存储数据，同时也能够请求并解析XML
4. 能够编写JSON文件存储数据，同时也能够请求并解析JSON

# 1. 概述
1. 是什么？  异步JavaScript和XML
2. 有哪些技术？ HTML、CSS、JS（DOM）、XMLHttpRequest（核心对象）
3. 作用：无刷新更新页面
4. 优点：按需更新，减少数据量。。。。
5. 缺点：URL-->资源

# 2. 同步异步请求 txt
1. 创建核心对象
2. 创建请求
3. 发送请求（同步和异步）
4. 处理数据（text--responseText  xml--responseXML  json--responseText--转换为对象）

# 3. XML
## 1. XML的编写（存储数据：文本存储、属性存储）
1. 文本存储<tag>data</tag>
2. 属性存储<tag attr="data"></tag>
## 2. XML的解析并显示
1. 获得数据 xhr.responseXML -----XML树
2. 解析（类比DOM进行解析）

# 4. JSON
## 1. JSON编写
1. 存一个对象{}
2. 存多个对象[{},{},{}]
## 2. JSON解析
1. responseText
2. JSON.parse(jsonstr) ----- JS对象
3. 对象.属性