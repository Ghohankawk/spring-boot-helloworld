# 项目介绍
这是采用最新的spring boot框架搭建而成

简单说一下开发调试流程，有2种方式运行该项目

##方式一
打开Application类，点击main方法执行即可。前提是你要注释掉pom.xml文件中的我说的那句注释，即scope那行。

##方式二
利用本地tomcat服务器，在build的时候，之前，运行maven命令，clean package -Dmaven.test.skip=true，即可，这种方式不用改pom文件

