# Express

node的快速极简的web开发框架

![EXPRESS](https://i.cloudup.com/zfY6lL7eFa-3000x3000.png "express")

[官网介绍](http://expressjs.com/)
 
[Zip下载地址](https://api.github.com/repos/strongloop/express/zipball)

[Github地址](https://github.com/strongloop/express)



### 安装
配置Node.js 和 Git bash 用于下载至本地
```sh
  $ npm  install express
```
### 特点
  - 鲁棒路由算法 --> needed to study
  - 专注于高性能
  - 超文本转移协议辅助对象(重定向,缓存等等)
  - 视图系统支持14+模板引擎
  - 内容协商机制
  - 快速生成应用的可执行文件
  
### 文档 & 社区
  - [网址和文档](http://expressjs.com/) -  [[库地址](https://github.com/expressjs/expressjs.com)]
  - 加入freenode IRC客户端进行[#express话题](https://webchat.freenode.net/?channels=express) 交流
  - 官方中间件 & 模块的 [Github代码组织](https://github.com/expressjs)
  - 访问 [维基百科](https://github.com/strongloop/express/wiki)
  - [Google 论坛](https://groups.google.com/forum/#!forum/express-js)
  
##### 高级技巧 
一定要去阅读 [Migrating from 3.x to 4.x ](https://github.com/expressjs/express/wiki/Migrating-from-3.x-to-4.x)这篇文章, 以及 [ New features in 4.x.](https://github.com/expressjs/express/wiki/New-features-in-4.x)这篇。

### 快速入手
着手express的最快速方式就是运用可执行文件 [express应用生成器](https://github.com/expressjs/generator) 来生成一个应用,如下所示:

安装可执行文件。可执行文件的主版本将会适配Express的版本:
```sh
    $ npm install -g express-generator@4
```

创建app:
```sh
    $ express /tmp/foo && cd /tmp/foo
```

安装依赖项:
```sh
    $ npm install
```

开启服务
```sh
    $ npm start
```

## 原理 
Express的运行原理是为HTTP服务提供小而健壮的工具, 是为单页面应用程序, 网站, 混合或者公共的HTTP应用程序接口提供一个更好的解决方案。

Express不会强制你去使用任何特定的ORM（数据关系映射）或者模板引擎。同时通过[Consolidate.js](https://github.com/tj/consolidate.js) (是一款基于js的模板引擎整合库，支持现今流行的多种模板引擎) 支持超过14模板引擎，可以快速的定制你的完美框架。

## 示例：
查看示例，克隆Express的仓库地址并且安装依赖项
```sh
    $ git clone git://github.com/strongloop/express.git --depth 1
    $ cd express
    $ npm install
```

然后运行你要运行的例子:
```sh
    $ node examples/content-negotiation
```

## 测试:
运行测试集，首先安装依赖项，然后运行 npm text :
```sh
    $ npm install
    $ npm test
```

# 感谢为此做出贡献的人
Express 原作者: [TJ Holowaychuk](https://github.com/tj)

当前主导维护者: [Douglas Christopher Wilson](https://github.com/dougwilson)

[所有与之做出贡献者列表](https://github.com/expressjs/express/graphs/contributors)

## TRY IT ANT TRY IT
