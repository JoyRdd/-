# 人事管理系统
# 期末作业
## 介绍

人事管理系统功能包括人事通讯,员工信息,人事考评,奖惩,培训管理,薪资管理,统计分析,和系统管理六大模块,对应人事工作基本流程:新员工入职档案建立,调动,辞职,员工信息的查询及工资管理等方面.系统管理可以根据不同的角色分配菜单权限设置,不同的用户授予不同角色,对人事结构,单位结构进行整体调配设置.在线聊天可以实现操作员之间讯息的及时通讯.
项目基于MVVM的前后端分离开发模式进行开发.MVVM即模型(Model)-视图(View)-视图模型(View Model),实现了数据视图的双向绑定.相对于MVC模式和MVP来说,MVVM是一个比较新的开发架构,它是一种将MVP模式与WPF相结合应用方式发展演变而成的新型开发架[1] .
前后端分离是指将前端和后端从之前的全部由后端负责中分离开来,不再共用一个Server,前端作为一个独立Serve存在[2].前后端通过接口使用HTTP协议交互,本项目使用vu实体属性outer做前端路由处理.页面跳转不在由后端处理,前后端只是数据的交互.前后端分离的好处在于降低了前后端的耦合性.当面对不同的硬件场景时,需要构建不同的界面,前后端分离之后,只需要扩展前端项目即可,不需要修改后端服务.
在动态权限处理方面,使用安全框架Spring Security,基于RBAC（Role-Based Access Control ）角色的访问控制模型,由该模型主要由鉴权和授权构成,鉴权基于Servlet中Filter原理处理,授权由系统管理员操作.RBAC 的主要思想是：权限是和角色相关的,而用户则被分配相应的角色作为其成员,这样就大大简化了权限的管理 [3] .

## 软件架构：
    前后端分离
## 后端技术栈

1. Spring Boot
2. Spring Security
3. MyBatis
4. MySQL
5. Redis
6. RabbitMQ
7. Spring Cache
8. WebSocket

## 前端技术栈

1. Vue
2. ElementUI
3. axios
4. vue-router
5. Vuex
6. WebSocket
7. vue-cli4

## 项目效果图

![image-20221029085636041](C:\Users\Administrator\AppData\Roaming\Typora\typora-user-images\image-20221029085636041.png)

![image-20221029085702759](C:\Users\Administrator\AppData\Roaming\Typora\typora-user-images\image-20221029085702759.png)

## 安装教程：

1.JDK 1.8

2.IEDA 2021.3.3

3.Microsoft SQLServer 2005

4.Resin 3.0.24

5.Tomcat 8.5

6.Redhat Enterprise Linux Server 5.0




## 小组成员：乔航 王宇涵 王誉儒 秦欣 秦梓豪 唐尧
