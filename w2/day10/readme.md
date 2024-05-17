# Ajax目标
1. 能够简述Ajax是什么？有什么用？优缺点？
2. 能够实现与服务器进行同步异步通信TXT
3. 能够编写XML文件存储数据，能够请求XML数据并解析
4. 能够编写JSON文件存储数据，能够请求JSON数据并解析

# 1. Ajax概述
1. 是什么？ 异步JS和XML
2. 作用？ 与服务器进行异步（同步）通信   无刷新更新页面 ----检测用户名是否被注册
3. 优点：异步通信提高效率、按需更新节省带宽、数据显示分离易于维护
4. 缺点：URL-->网页内容（对搜索引擎支持不友好、不支持前进、后退）

# 2. 同步异步请求
1. 步骤（四步）
2. 异步（触发函数  xhr.readyState==4 && xhr.status==200）

# 3. XML请求和解析
## 1. 编写XML
1. 必须要有根标记
2. 标签成对
3. 属性要加引号
## 2. 获取并解析
1. data = xhr.responseXML
2. 解析类比DOM（innerHTML、getAttribute()）

# 4. JSON请求和解析
## 1. 编写JSON
1. {"key":value,"key":value}
2. [{},{},{}]
## 2. 请求并解析
1. data = xhr.responseText    将文本转换为JS对象 JSON.parse(data)
2. 对象.属性