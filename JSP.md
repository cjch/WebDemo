# JSP

##开发环境搭建 Eclipse + Tomcat

配置jsp开发环境，按照下面的教程实现即可。

- [Eclipse JSP/Servlet 环境搭建](http://www.runoob.com/jsp/eclipse-jsp.html)
- [Tomcat SSL配置](http://www.oschina.net/question/12_23148?fromerr=qVX3TcV3)

问题：按照上面的教程配置https，可能会导致eclipse中的项目不能使用https打开。  
原因：在eclipse中启动tomcat，本地的tomcat配置文件会被eclipse中的server重置。  
解决方法：eclipse工程列表中有一个Servers工程，里面有tomcat的配置文件，按照教程配置这些文件即可。 
