# 网上购书系统
综合应用实验
--------------------
2.1 任务描述

   通过实现一个简单的网上购书小网站，掌握jsp、servlet、struts的基本实现技术。

2.1.1 用户角色：普通用户（匿名用户或Internet用户）、会员和系统管理员

2.1.2 应用场景：
  （1）普通用户通过该购书平台可以浏览所有的图书信息；
  （2）普通用户可以注册为会员用户；
  （3）会员用户可以管理其个人基本资料；
  （4）会员用户在登录状态下，可以选购图书，管理购书清单，下定单（模拟已经结帐）；
  （5）系统管理员可以进行用户管理（浏览或更新、删除用户资料）
  （6）系统管理员需要录入图书目录信息，并维护这些信息；
  （7）系统管理员可以查看所有当前定单（包括已结和未结帐）
  （8）系统管理员可以查看在线用户（选做） 

2.1.3 数据需求
  （1）用户数据[用户名，密码，角色或权限]
  （2）图书数据[书名，出版社，出版日期，ISBN，图书描述，图书封面，单价]
  （3）购书清单[图书列表(含数量)，创建日期，最后更新日期]
  （4）定单[图书列表(含数量)，总价，下单日期，结帐日期]
  （5）在线用户[guest/会员,ip,url,在线时间] （选做）
  （5）日志[URL,Access IP，action,...]（选做）
	
2.2 实现要求

   基本要求：能够利用每章所学的知识点来构建整个系统。
  （1）第一阶段：JSP + Servlet + Javabean + JDBC，采用Model1或Model2都可以。
  （2）第二阶段：将第一阶段的实现改为struts2 + JavaBean + JDBC
   包含技术点：action，struts标签，OGNL，拦截器，校验器，文件上载，分页...
  （3）第三阶段：将第二阶段的实现改为struts2 + hibernate
  （4）第四阶段：将第三阶段的实现改为struts2 + spring + hibernate (选做)

2.3 提交

   打包并提交整个项目和实验报告(电子版)，有基本的系统设计、基本使用说明，有关键代码说明，有web页面运行界面截图
