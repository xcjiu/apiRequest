# apiRequest
## api请求模拟器
这是一个简单的模拟远程API访问的页面，整个脚本就一个html文件，用浏览器打开就可用。
#
实现原理是用ajax异步请求，发送数据并接收信息
```
点击 PARAMETERS 按钮传参
点击 add param 按钮添加参数
点击 删除 按钮删除不要的参数
点击 Send 按钮或按回车键发送请求

```
### 主要实现以下功能
- [x] 请求方式支持：GET,POST,PUT,DELETE,HEAD,OPTIONS,PATCH
- [x] 传入多个参数 或 删除
- [x] 显示部分http响应头信息
- [x] 显示请求结果，支持无限级数组数据递归显示
#
#### 页面效果如下：
![image](https://github.com/xcjiu/apiRequest/blob/master/api_1.png)
#
![image](https://github.com/xcjiu/apiRequest/blob/master/api_2.png)
#
![image](https://github.com/xcjiu/apiRequest/blob/master/api_3.png)




