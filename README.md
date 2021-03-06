JeeWx 微信管家平台，简称“捷微”.
===============
  （是一款免费开源的JAVA微信公众账号开发平台）
===============
当前最新版本： 2.4.1（发布日期：20160822）

![github](http://img.blog.csdn.net/20140706133601296?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvemhhbmdkYWlzY290dA==/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/Center "jeewx")
<br>平台介绍：

一、简介
-----------------------------------
Jeewx是一个开源、高效、敏捷的微信开发平台，采用JAVA语言基于Jeecg快速开发框架实现，Jeewx实现了微信平台的基础功能，便于用户二次开发。jeewx采用微服务框架，插件开发方式实现微信功能，不同的插件实现不同的微信功能。
 升级说明： JEEWX后续升级，会采用插件方式，当前已经推出“微信企业号插件”，更多插件敬请期待。。
【更多插件：微信公众号、微信企业号、支付服务窗、QQ公众号、微博等】

主要特性
-----------------------------------
* 	1、JEEWX 基于快速开发平台jeecg 3.4.4 版本开发，采用SpringMVC+Hibernate4+UI库+代码生成器+Jquery+Ehcache等主流架构技术
*   2、支持企业快速开发，完善的用户组织机构，报表，强大的代码生成器快速有效的提高开发效率
*   3、开源免费，jeewx遵循Apache2开源协议,免费提供使用。
*   4、支持微信公众号管理（针对：微信公众订阅号、微信公众号服务号）
*   5、支持微信企业号管理（针对：微信企业号）
*   6、详细的二次开发文档，并不断更新增加相关开发案例提供学习参考
*   9、采用微服务架构jeecg-p3，支持微信功能插件化开发，更易于定制和二次开发

主要功能
-----------------------------------
*   1，微信接口认证
*   2，菜单自定义
*   3，文本管理和回复
*   4，关注欢迎语
*   5，关键字管理
*   6，文本模板管理
*   7，图文模板管理
*   8，账号管理
*   9，用户管理
*   10，角色管理
*   11，菜单管理
*   12, 多用户多公众号
*   13，微信大转盘
*   14，微信刮刮乐
*   15，微信CMS
*   16，自定义接口回复
*   17，翻译
*   18，天气
*   21, author2.0链接
*   22, 微信插件机制
*   23, 用户消息
*   24, 微信第三方平台（全网发布）
*   25, 支持微信企业号(微信企业号管理平台)


JEEWX企业号平台（独立插件模块）
-----------------------------------
*   1，微信企业号管理
*   2，微信应用管理
*   3，素材管理：文本素材
*   4，素材管理：图文素材
*   5，菜单管理
*   6，通讯录管理
*   7，用户管理
*   8，关键字管理
*   9，关注回复管理
    源码下载地址：http://yun.jeecg.org

开发环境
-----------------------------------
  eclipse + maven + jdk7 + tomcat6 + mysql_5.0.37 （注意： 不支持jdk8;）

系统安装
-----------------------------------
* 	1、将项目采用maven方式导入eclipse中，通过maven下载项目依赖。
* 	2、采用Mysql手工创建数据库jeewx 采用UTF-8编码，执行捷微数据初始化SQL脚本 ：doc/db/jeewx-2.4.1.sql
* 	3、采用maven方式启动项目，首次在浏览器中访问 http://localhost:8080/jeewx/，默认admin登录，一个账号只能配置一个微信公众账号。
* 	4、微信域名配置（重要）
* 	   修改：src/main/resources/sysConfig.properties
* 	   参数：domain={http://localhost:8080/jeewx/}
* 	5、服务器配置      
        URL:   http://*地址*/jeewx/wechatController.do?wechat<br>
        Token:  jeecg<br>
*   6. [开发环境搭建入门](http://www.jeecg.org/forum.php?mod=viewthread&tid=2080&extra=page%3D2) 
*   7. Jeewx依赖本地Maven仓库下载 (http://git.oschina.net/jeecg/jeecg-local-maven) 

技术交流
-----------------------------------
* 	论 坛:  www.jeecg.org
* 	QQ 群:  群④289709451、①287090836（满）、③175449166（满）、②129190229（满）
* 	官 网:  www.jeewx.com
* 	邮 箱： jeecg@sina.com


技术文档
-----------------------------------
* [JEEWX 系统操作手册](http://blog.csdn.net/zhangdaiscott/article/details/50950739)
* [JEEWX 开发环境搭建入门](http://blog.csdn.net/zhangdaiscott/article/details/50915206)
* [JEEWX 开发入门视频](http://www.jeecg.org/forum.php?mod=viewthread&tid=2309&extra=page%3D1)
* [JEEWX 入门常见问题](http://www.jeecg.org/forum.php?mod=viewthread&tid=1830&extra=page%3D1)
* JEECG 应用插件下载中心：[http://yun.jeecg.org](http://yun.jeecg.org)

商业版介绍
-----------------------------------
*   在线演示: [http://www.jeewx.com/jeewx](http://www.jeewx.com/jeewx)
*   体验账号：ceshi/123456 (可注册)
*   JEEWX官网：[www.jeewx.com](http://www.jeewx.com)

体验公众号 
-----------------------------------
    官方公众号："JEECG"  "H5互动汇"
![github](http://img.blog.csdn.net/20160323155143399?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQv/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/Center "jeewx")
![github](http://img.blog.csdn.net/20160323154916164?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQv/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/Center "jeewx")


系统截图 
-----------------------------------
![github](http://img.blog.csdn.net/20160822173828381?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQv/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/Center "jeewx")
![github](http://img.blog.csdn.net/20160822173833177?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQv/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/Center "jeewx")
![github](http://img.blog.csdn.net/20160323152508827?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQv/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/Center "jeewx")
![github](http://img.blog.csdn.net/20160323153059001?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQv/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/Center "jeewx")
![github](http://img.blog.csdn.net/20160323153104923?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQv/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/Center "jeewx")
![github](http://img.blog.csdn.net/20160323153117501?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQv/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/Center "jeewx")
![github](http://img.blog.csdn.net/20160323153122251?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQv/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/Center "jeewx")
