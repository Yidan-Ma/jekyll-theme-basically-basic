---
title: jekyll搭建个人个人网站，你奔溃了吗
date: 2021-01-08
excerpt_separator: "<!--more-->"
categories:
     - 网站设计
---

期末项目jekyll搭建个人网站，你是不是崩溃了好几天呢？

<!--more-->

## 如何将本地，GitHub desktop，github，gitee关联同步

1.在github中寻找一个合适的模板项目，点击右上角 FORK，新建一个分支

2.在gitee中右上角“+”处点击 从Gihub导入仓库，导入已FORK项目，添加强制同步的github项目仓库url，新建一个一样的分支

3.在GitHub desktop导入github项目仓库，新建一个一样的分支，然后就可以直接在本地修改同步啦

## 如何利用gitee部署
1.进入_config.yml文件中，点击编辑，修改lang，title，description，baseurl，url，theme

2.修改theme时候，在41行句首加入“#”并加入一个空格，消除该行代码效果

3.注意语法问题

## gitee部署失败的原因
1.没有在_config.yml文件中修改个人配置

2.修改配置过程中url错误

3.在_config.yml文件中修改个人配置时候有语法错误

## 上传文章的时候为什么gitee pages不会显示
1.md语法错误

2.md文件命名错误

3.网络延迟，多次刷新或者等到第二天就能看到了

## pages时出现403 Forbidden的原因和解决方法
1.原因：在一段时间内过多访问此网站，被防火墙拒绝访问了

2.解决方法：找到浏览器的设置，点击清除浏览数据，再把浏览器关掉或者电脑重启就好啦
