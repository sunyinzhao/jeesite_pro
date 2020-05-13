# jeesite_pro
一个基于jeesite快速开发框架的demo
# 引言
JeeSite 是一个 Java EE 企业级快速开发平台，基于经典技术组合（Spring Boot、Spring MVC、Apache Shiro、MyBatis、Beetl、Bootstrap、AdminLTE）采用经典开发模式，让初学者能够更快的入门并投入到团队开发中去。在线代码生成功能，包括核心模块如：组织机构、角色用户、菜单及按钮授权、数据权限、系统参数、内容管理、工作流等。采用松耦合设计；界面无刷新，一键换肤；众多账号安全设置，密码策略；在线定时任务配置；支持集群，支持SAAS；支持多数据源；支持微服务。

JeeSite 快速开发平台的主要目的是能够让初级的研发人员快速的开发出复杂的业务功能（经典架构会的人多），让开发者注重专注业务，其余有平台来封装技术细节，降低技术难度，从而节省人力成本，缩短项目周期，提高软件安全质量。

JeeSite 1.x 自 2013 年发布以来已被广大爱好者用到了企业、政府、医疗、金融、互联网等各个领域中，JeeSite 依架构简单精良、易于扩展、大众思维的设计模式，深入开发者的内心，并得到一致好评，于2016和2017连续两年获得开源中国《最受欢迎中国开源软件》奖杯，期间也帮助了不少刚毕业的大学生作为入门教材，快速的去实践。

JeeSite 4.x 的升级，作者结合了多年总结和经验，以及各方面的应用案例，对架构完成了一次全部重构，也纳入很多新的思想。不管是从开发者模式、底层架构、逻辑处理还是到用户界面，用户交互体验上都有很大的进步，在不忘学习成本、提高开发效率的情况下，安全方面也做和很多工作，包括：身份认证、密码策略、安全审计、日志收集。

# 4.x 的新特性及优势：http://jeesite.com/?t=281645

# 技术选型
主框架：Spring Boot 2.0、Spring Framework 5.0、Apache Shiro 1.4、J2Cache

持久层：Apache MyBatis 3.4、Hibernate Validation 6.0、Alibaba Druid 1.1

视图层：Spring MVC 5.0、Beetl 2.9 替换JSP、Bootstrap 3.3、AdminLTE 2.4

前端组件：jQuery 1.12、jqGrid 4.7、layer 3.0、zTree 3.5、jquery-validation

工具组件：Apache Commons、Logback 1.1、Jackson 2.8、POI 3.14、Quartz 2.2

# 技术选型详情：http://jeesite.com/?t=273599

# 内置功能
http://jeesite.com/?t=270187

# 生态系统
分布式微服务系统（Spring Cloud）：https://gitee.com/thinkgem/jeesite4-cloud

JFlow工作流引擎：https://gitee.com/thinkgem/jeesite4-jflow ：http://ccflow.org

内容管理模块（CMS）：https://gitee.com/thinkgem/jeesite4-cms【敬请期待】

# 快速体验
在线演示

地址：http://demo.jeesite.com/

账号：system

密码：admin

# 本地运行
环境准备：JDK 1.8、Maven 3.3、MySQL 5.7

下载源码：https://gitee.com/thinkgem/jeesite4/attach_files

打开文件：/web/src/main/resources/config/application.yml 配置JDBC连接

执行脚本：/web/bin/init-data.bat 初始化数据库

执行脚本：/web/bin/run-tomcat.bat 启动服务即可

浏览器访问：http://127.0.0.1:8980/js/ 账号 system 密码 admin

部署常见问题：http://jeesite.com/?t=284210

开发环境

部署运行：http://jeesite.com/?t=267354

常见问题：http://jeesite.com/?t=284210

# 在线文档  http://docs.jeesite.com

# 授权协议声明
已开源的代码，授权协议采用 AGPL v3 + Apache Licence v2 进行发行。

您可以免费使用、修改和衍生代码，但不允许修改后和衍生的代码做为闭源软件发布。

修改后和衍生的代码必须也按照AGPL协议进行流通，对修改后和衍生的代码必须向社会公开。

如果您修改了代码，需要在被修改的文件中进行说明，并遵守代码格式规范，帮助他人更好的理解您的用意。

在延伸的代码中（修改和有源代码衍生的代码中）需要带有原来代码中的协议、版权声明和其他原作者规定需要包含的说明（请尊重原作者的著作权，不要删除或修改文件中的@author信息）。

您可以应用于商业软件，但必须遵循以上条款原则（请协助改进本作品）。

关系平台的发展战略考虑，底层部分代码暂未开源，但这不影响您的二次开发。

请知悉社区版，用户数不可超过100个，最大允许20个用户同时在线（不含匿名）。


