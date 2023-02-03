# Spring boot基础面试题
## 使用spring boot的优势是什么？
1. 易于理解和开发spring的应用
2. Spring 
3. 提高开发效率
4. 配置文件最少化
5. 不需要使用XML进行配置，配置只需要通过极少的注解就能完成

## Spring Boot的关键组件是什么
1. Spring Boot 自动装配
2. Spring Boot CLI
3. Spring Boot starter POMs.
4. Spring Boot 

## 

## Spring boot starter 模块都有什么依赖？
比较常用的如下：
1. Data JPA
2. Test
3. Security
4. Web
5. Mail
6. Thymeleaf

## Spring boot 是如何工作的？
首先在Spring Boot 启动类的main方法上添加@SpringBootApplication注解，其次使用@ComponentScan注解去自动扫描项目下的模块

## @SpringBootApplication 注解的内部实现了什么？

## 在启动类文件中使用@ComponentScan的目的是什么？
在应用初始化的时，Spring Boot会扫描所有的beans和package声明，@ComponentScan的作用是保证已声明的beans和package都能正常加载

## Spring boot 应用是如何启动的？
Spring Boot的启动类似于Java程序，在一个Spring boot的项目中，必须要有一个main方法。这个方法是项目的入口文件，它调用SpringApplication.run方法来执行程序.

## 什么是启动依赖？

## 什么是Spring初始化？

## 什么是Spring Boot CLI和它的好处？

## 最常用的Spring Boot CLI命令是什么？

# Spring Boot 进阶

## Spring Boot 基本的依赖注解
@EnableAutoConfiguration: 自动扫描和装配所有的beans
@SpringBootApplication： 标识Spring Boot应用的主方法，这个注解和合并了@configuration, @EnableAutoConfiguration和@ComponentScan注解和它们的默认属性

## 什么是Spring Boot的依赖管理？

## Spring Boot能创建一个没有web的应用吗？

## Spring Boot嵌入式的Tomcat端口能被修改吗？
能，在配置文件中使用server.port来指定tomcat的启动端口。

## Spring Boot的tomcat默认端口是多少？
tomcat启动的端口默认是8080，它可以在配置文件中被指定。

## Spring Boot中嵌入式的tomcat能被覆盖或替换吗？
能。可以在pom.xml修改需要使用的服务器，例如jetty

## 

## 如何在一个特定的类中禁用自动装配
可以使用@enableAutoCOnfiguration中的exclude参数

## @RestController 注解的作用

## @RestController和@Controller的不同

## 描述通过Spring boot的HTTPS请求的流程
在Spring Boot应用中，遵循MVC模式，它的请求流程如下  
客户端<--HTTPS Request-->控制器<---->业务层（依赖注入）<--数据库操作-->模型层 

## RequestMapping和GetMapping的不同

## Profiles在Spring Boot中的作用是什么

## 什么是Actuator？它的优点是什么？

## 在Spring Boot中如何使用Actuator

## 