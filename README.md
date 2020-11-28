# MyBlog
(springboot+JPA)-小而美的个人博客项目

作者：吴建虎

项目的实现是跟随b站李仁密老师的视频学习的，有兴趣的可以了解一下（讲的挺好的，受益良多）  
链接地址：https://www.bilibili.com/video/BV1KJ411D7bW

博客连接：http://xiaohuou.cn/

数据持久层使用了JPA,目录中有blog.sql文件，创建一个blog的数据库，运行sql文件生成对应的表。maven环境配置完，记得安装Lombok插件。
项目运行前修改数据库的username和password。后台登录密码默认为123456，如需修改密码只需将util包下MD5Utils类的运行结果放入数据库即可登录

## 功能:  
前端展示 + 后台管理

## 技术栈:  
后端：SpringBoot + JPA   
数据库: MySQL  
前段UI：Semantic UI框架 + thymeleaf模板

## 工具与环境:  
IDEA  
navicat  
jdk8  
maven-3.6.3  
mysql-8.0.17  
springboot-2.3.5
