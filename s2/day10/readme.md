# Ajax(异步A地向服务器发起请求JS，获取响应数据TXTXML、JSON)
1. 能够描述Ajax是什么？特点？优缺点？核心构成？
2. 能够同步/异步的获取text数据
3. 能够根据需要编写XML文件，同时能够解析XML数据
4. 能够根据需要编写JSON文件，同时能够解析JSON
# 1. Ajax概述
1. 是什么？（技术的组合JS+DOM+HTML、CSS+核心对象XMLHttpRequest）
2. 特点：无刷新页面更新页面内容（验证码）
3. 优缺点：优点（占用带宽更小、效率更高。。。）
# 2. text的同步异步请求
1. 创建核心对象
2. 创建请求
3. 发送请求
4. 处理数据（同步、异步）xhr.responseText
扩展：数据是否影响后续操作（是：同步）
# 3. XML请求及解析
## 1. XML编写
1. 必须要有根标记
2. 所有标记都必须成对出现
3. 存储数据：文本存储（innerHTML）、属性存储（getAttribute）
## 2. 请求XML数据并解析
1. xhr.responseXML
2. 类似于DOM节点树来获取XML数据
# 4. JSON请求及解析
## 1. JSON编写
1. 可以是{}一个对象
2. 可以是[{},{},{}] 多个对象
## 2. JSON请求及解析
1. xhr.responseText（纯文本）
2. 将纯文本转换为JS对象【关键，重要】 JSON.parse(jsonstr)
3. 通过对象的属性读取  stu.name  stu["name"]