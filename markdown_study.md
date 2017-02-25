# Markdown--从入门到精通
#### 导语
> [Markdown](http://zh:wikipedia.org/wiki/Markdown)是一种轻量级的标记语言

## 一、认识Markdown

在刚才

## Markdown 官方文档
> 这里可以看到

* [创始人](http://darring)
* [中文版语法说明](http://wooo)

### 使用markdown的有点
* 专注你的文字内容而不是排版样式
* 轻松的导出HTML、PDF和本身的.md文件
* 纯文本内容,兼容所有的文本编辑器与字处理软件
* 可读,直观。适合所有人的写作语言

### 我该用什么工具？
![Mou icon](http://mouapp.com/Mou_128.png)

在Mac OS X上
![]()

## 表格
| Tables  | are | cool |
| ------- |:---:| ----:|
| col 2   | re  | aaa  |
| col 3   | ccc | vbbb |

## 无序列表
* 1
* 2
* 3

## 有序列表
1. 1
2. 2
3. 3

## 引用

> 这是引用

## 图片
![baidu](https://ss0.bdstatic.com/5aV1bjqh_Q23odCf/static/superman/img/logo/bd_logo1_31bdc765.png)

## 连接
[baidu](http://www.baidu.com)

## 粗体
**这是粗体**

## 斜体
*这是斜体*


## 行内代码框
` console.log(11);
function(){}
`

## 分隔线
***

## 块代码框
```
self.app.use(function (req, res, next) {
           if (self.filterFuncs.length) {
               Async.eachSeries(self.filterFuncs, function (func, callback) {
                   func(req, res, function (err) {
                       callback(err);
                   });
               }, function (err, resp) {
                   next(err);
               });
           } else {
               next();
           }
       });
       self.loadRoutes(self.routePath);
```

    
