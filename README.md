# Learn-Spring-Framework
This repository shows how to configure Spring Framework and make a project using Spring. 

**What you need?**
**Softwares & Pre-requisites:**
1. Intellij/Ecllipse/NetBeans
2. TomcatSErver
3. MySQL for Database
4. Sqlyog, workbench, or Phpmyadmin for mysql gui

**Steps to be followed to make a Spring Project:**
1. Create Maven poject
2. Adding dependencies -> spring core, spring context
3. creating beans - java pojo
4. creating configuration file -> config.xml
5. Setting injection
6. Main Class : which can pull the object and use

**OR**

visit: Spring Init(https://start.spring.io/)
![WhatsApp Image 2023-10-31 at 22 25 16_4a15c0bc](https://github.com/Shimork04/Spring-Framework/assets/111634234/6e613a38-02ae-4766-ae04-5205068030d8)
- you can also add dependencies according to your project requirements. eg: Spring Web, Mysql etc


**'config.xml' file configuration:**
<?xml version="1.0" encoding="UTF-8"?>
//as per this project, you can configure according to your need
<beans xmlns="http://www.springframework.org/schema/beans"
       xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
       xmlns:context="http://www.springframework.org/schema/context"
       xmlns:p="http://www.springframework.org/schema/p"
       xsi:schemaLocation="http://www.springframework.org/schema/beans
       http://www.springframework.org/schema/beans/spring-beans.xsd
       http://www.springframework.org/schema/context
       http://www.springframework.org/schema/context/spring-context.xsd">
</beans>


Running on Port 8080 -> locolhost:8080/welcome
![WhatsApp Image 2023-10-31 at 22 23 58_9ea7a91f](https://github.com/Shimork04/Spring-Framework/assets/111634234/60bb7af3-aedd-47b3-b63f-dcb151a318f4)


Snapshot of spring file running in terminal, apache tomact server is installed by default.
![WhatsApp Image 2023-10-31 at 22 24 33_7ccbe56d](https://github.com/Shimork04/Spring-Framework/assets/111634234/10407b60-97d1-4f71-8e2c-7ab9b3a28a65)

