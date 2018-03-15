# 项目结构
|模块名|文件目录|说明|
|:---:|:---:|:---:|
|http服务|web|包含API接口具体实现，基于 Flask Web框架|
|爬虫实现|crawlers|爬虫的具体实现|
|爬虫任务执行|jobs|基于消息队列(beanstalkd)的任务调度|
|数据操作|models|对数据库的 CRUD 操作实现, 基于 Sqlalchemy |

# HTTP 方法说明

* GET（SELECT）：从服务器取出资源（一项或多项）。
* POST（CREATE）：在服务器新建一个资源。
* PUT（UPDATE）：在服务器更新资源（客户端提供改变后的完整资源）。
* PATCH（UPDATE）：在服务器局部更新资源（客户端提供改变的属性）。
* DELETE（DELETE）：从服务器删除资源。
* HEAD：获取资源的元数据。
* OPTIONS：获取信息，关于资源的哪些属性是客户端可以改变的。

# 接口实现

- [x] 登录注册
- [x] 需要登录的接口，使用装饰器添加验证
- [x] 登录将爬取的平台
- [ ] 创建饿了么商家爬虫
- [ ] 创建饿了么商家菜品
- [ ]
