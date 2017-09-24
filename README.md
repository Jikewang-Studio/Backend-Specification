<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->


- [代码规范](#%E4%BB%A3%E7%A0%81%E8%A7%84%E8%8C%83)
- [工具使用](#%E5%B7%A5%E5%85%B7%E4%BD%BF%E7%94%A8)
- [开发流程](#%E5%BC%80%E5%8F%91%E6%B5%81%E7%A8%8B)
- [推荐一些书和资料](#%E6%8E%A8%E8%8D%90%E4%B8%80%E4%BA%9B%E4%B9%A6%E5%92%8C%E8%B5%84%E6%96%99)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

# 代码规范

我们采用《阿里巴巴技术规范手册》


# 工具使用

**版本控制**

git(github)

**单元测试**

Junit

**项目管理**

Maven

**web 接口测试**
postman

**api文档**

rap

**接口联调**
- 本机自测：前端开发人员需要自己安装Tomcat，MySQL并下载后端运行文件
- 远程测试：直接使用对方IP进行测试(可使用Nginx反向代理达到更改一处IP即可)

_**Web应用测试**
Apache JMeter_

# 开发流程

功能开发->单元测试->功能测试->Code Review(FindBugs，CheckStyle)->集成测试(接口联调)->发布


# 推荐一些书和资料
1. 《轻量级Java EE 企业级应用实战》里面有JSP，Servlet及Struts2，Spring，Hibernate框架的介绍
2. 《深入浅出MySQL》里面有MySQL的开发和优化
3. 《深入浅出Mybatis》，《Spring实战》，《Maven实战》也要买来看看，git学习直接看这个教程就好了[Git教程](https://www.liaoxuefeng.com/wiki/0013739516305929606dd18361248578c67b8067c8c017b000/)，SSH框架和SSM框架的搭建和和遇到的问题也要弄明白
4. 算法的话，可以买《算法》或者去牛客网刷题
5. 代码质量的话，可以买《Effective Java》和《Clean Code》和《重构》
6. 技术趋势：开发者头条，segmentfault，掘金，CSDN，infoq

可以趁开学打折的时候买
