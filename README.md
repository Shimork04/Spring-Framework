# Learn-Spring-Framework
This repository shows how to configure Spring Framework and make a project using Spring. 

What you need?
Softwares & Pre-requisites:
1. Intellij/Ecllipse/NetBeans
2. TomcatSErver
3. MySQL for Database
4. Sqlyog, workbench, or Phpmyadmin for mysql gui

Steps to be followed to make a Spring Project:
1. Create Maven poject
2. Adding dependencies -> spring core, spring context
3. creating beans - java pojo
4. creating configuration file -> config.xml
5. Setting injection
6. Main Class : which can pull the object and use

'config.xml' file configuration:
<?xml version="1.0" encoding="UTF-8"?>
<beans xmlns="http://www.springframework.org/schema/beans"
       xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
       xmlns:context="http://www.springframework.org/schema/context"
       xmlns:p="http://www.springframework.org/schema/p"
       xsi:schemaLocation="http://www.springframework.org/schema/beans
       http://www.springframework.org/schema/beans/spring-beans.xsd
       http://www.springframework.org/schema/context
       http://www.springframework.org/schema/context/spring-context.xsd">
       
</beans>
