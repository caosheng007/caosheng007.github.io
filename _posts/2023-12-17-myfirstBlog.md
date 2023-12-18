---
layout:       post
title:        "曹晟的第一篇博客"
author:       "Caosheng007"
header-style: text
catalog:      true
tags:
header-img: "img/post-bg-2015.jpg"
    - 碎碎念
---

> 这是我的第一篇博客

记录一下，这是我的第一篇博客， 就记录一下这个博客是如何搭建起来的把。

关键是使用了[GitHub Pages](https://pages.github.com/) + [Jekyll](http://jekyllrb.com/) 快速 Building Blog 的技术方案，很方便。

首先第一步需要再Github上创建一个repo, repo的名字要为格式为 'username.github.io', 所以在我这里就是caosheng007.github.io

创建之后，该repo放入一个网站项目， 当输入网址时 https://caosheng007.github.io/ 时，就会自动将网页部署加载，十分方便，不需要额外的购买服务器和域名，能省钱，嘿嘿：）


网站项目是参照一位前端大佬的开源项目，可以直接fork他的项目， 克隆然后到自己的本地，修改一下配置，在_posts下面就可以按照md的格式开始写了。

在这里需要下载Jekyll 可以实现本地的部署和调试， 具体步骤可以参考下面的帖子。

[参考帖子](https://www.jianshu.com/p/58e2c5ea3103)


中间出现了一个小小的bug
windows 安装的时候碰到了问题：

ruby setup.rb 时显示权限不够

解决方法:

1. 在搜索栏中使用管理员运行

2. 再cd 进入到用户的工作目录

```Plain Text
cd C:\Users\Caosh 
```


继续操作就不会有权限问题了


