# AgriculturalProducts
大二作业，农产品交易平台。

##### 2020-09-17

将大二的时候做的这个javaweb工程再重新部署一次

工具：mac+idea

实现：tomcat8.5.581+mysql8.0+jdk1.8

错误与问题：

- 连接数据库的jar版本过低（jar和mysql版本不对，导致连接失败）
- 连接数据库相关代码语句不适用8.0版本mysql
- 代码里面原本就有些导包代码错误（有两个包没注意，把sql的包里的库用成了mysql的包里的库）
- 连接数据库代码在servlet里重复（已经改进）
- sql语句表名大写会导致错误（老版本没有错，新版本会出错）
- 搜索产品那个功能写的有问题（但是我也懒的改了）
- 多个版本的jar放进了jdk导致冲突混淆（容易混淆）