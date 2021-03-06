SpringOA简介
========

基于SpringMVC+Shiro+Activiti 5.16 的简单OA，可以快速入门Activiti学习用。<br>
推荐Fork本项目的 [EasyUI分支](https://github.com/zhaoml529/Spring-Activiti5.16-Shiro/tree/EasyUI "推荐Fork此分支项目")！

框架简介
--------
通过本项目系统的学习了Activiti的相关功能。<br>
框架以Spring Framework为核心、Spring MVC作为模型视图控制器、Shiro作为权限框架、Hibernate作为数据库操作层。<br>
本项目也可以为学习SpringMVC的同学提供帮助。<br>
本项目以查询待办任务、查待受理任务、查看运行中的流程以及流程控制中的一些问题为基础入门Activiti。<br><br>
演示事例有请假流程实例、报销流程实例、薪资调整流程实例等功能。<br>
实现了流程的签收、委派、转办、跟踪、撤销、跳转（向前和回退）至指定活动节点等功能。<br>
可以通过后台管理，动态部署流程、动态设定用户任务的处理人（运行中的流程也可以调整处理人）<br>
继承Activiti自带的modeler,实现在线设计流程文件。<br><br>
Shiro实现登录认证和权限控制，结合Ehcache缓存权限列表，毕竟权限表并不是总在变化。
用户在线列表，可以强制踢出。Shiro的密码的加密解密，并发登陆、会话管理等功能。

框架版本
--------
<ul>
<li>Activiti 5.16</li>
<li>Spring-4.0.0.RELEASE</li>
<li>Shiro-all-1.2.3</li>
<li>Hibernate-4.2.2.Final</li>
<li>Hibernate-validator-5.1.3.Final</li>
<li>validation-api-1.1.0.GA</li>
</ul>

数据库
-------
<ul>
<li>目前只支持MySql,建议MySql 5.5及以上</li>
</ul>


后续功能
--------
1.加入安全框架Shiro. ---已实现<br>
2.加入缓存 ehcache. --已实现<br>
3.前端页面 EasyUI，请查看EasyUI分支:https://github.com/zhaoml529/Spring-Activiti5.16-Shiro/tree/EasyUI<br>

首页
--------
![](https://github.com/zhaoml529/SpringOA/raw/master/WebContent/WEB-INF/images/main.jpg)  
