# basic_spring_mvc
basic_spring_mvc

【Spring】Spring MVC原理及配置详解 - CSDN博客
http://blog.csdn.net/jianyuerensheng/article/details/51258942
Spring mvc HandlerMapping 实现机制 - 简书
http://www.jianshu.com/p/c92197e1c892

org.springframework.web.servlet.handler.SimpleUrlHandlerMapping
通过配置请求路径和Controller映射建立关系，找到相应的Controller
org.springframework.web.servlet.mvc.support.ControllerClassNameHandlerMapping
通过 Controller 的类名找到请求的Controller。
org.springframework.web.servlet.handler.BeanNameUrlHandlerMapping
通过定义的 beanName 进行查找要请求的Controller
org.springframework.web.servlet.mvc.annotation.DefaultAnnotationHandlerMapping
通过注解 @RequestMapping("/userlist") 来查找对应的Controller。
：：：
其中DefaultAnnotationHandlerMapping是通过正则进行匹配找到的