# Ajax目标
1. 复述Ajax是什么？构成？作用？优缺点？
2. 能够使用Ajax实现同步/异步请求txt数据
3. 能够根据需要编写XML文件，同步异步能够请求XML数据并解析数据
4. 能够根据需要编写JSON文件，同步异步能够请求JSON数据并解析数据

# 1. Ajax概述
1. 是什么？构成？--异步的JS和XML，技术的组合（HTML、CSS、JS【DOM】、XMLHttpRequest）
2. 作用？---无刷新更新页面---注册账号
3. 优点：效率高，按需更新，数据显示分离
4. 缺点：URL（没有变）--> 内容（改变）

# 2. 同步异步请求文本数据
1. Ajax开发步骤（四步）
2. 如何使用异步 xhr.responseText

# 3. XML请求和解析
## 1. XML的编写
1. 必须有根标记
2. 所有标签要成对（自定义）
3. 存储数据（文本存储、属性存储）
## 2. 获取XML并解析
1. data = xhr.responseXML
2. 解析：类比DOM树

# 4. JSON请求和解析
## 1. JSON
1. JS对象 var x= {}
2. {一个对象}  [{},{}]
## 2. 获取JSON并解析
1. data = xhr.responseText  ---> JS对象
2. obj = JSON.parse(jsonstr);//推荐此方法      obj = eval("("+jsonstr+")");
3. 解析： 对象.属性