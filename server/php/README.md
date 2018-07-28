小程序商城
===============

主要特性包括：

 + 采用容器统一管理对象
 + 支持Facade
 + 注解路由支持
 + 路由跨域请求支持
 + 配置和路由目录独立
 + 取消系统常量
 + 助手函数增强
 + 类库别名机制
 + 增加条件查询
 + 改进查询机制
 + 配置采用二级
 + 依赖注入完善
 + 支持`PSR-3`日志规范
 + 中间件支持（V5.1.6+）
 + Swoole/Workerman支持（V5.1.18+）


> 运行环境要求PHP5.6以上。

## 安装

使用composer安装

~~~
composer install
~~~

启动服务

~~~
php think run
~~~
或
~~~
php think swoole
~~~

然后就可以在浏览器中访问

~~~
http://localhost:8000
~~~

更新框架
~~~
composer update topthink/framework
~~~

> 可以使用php自带webserver快速测试
> 切换到根目录后，启动命令：php think run

