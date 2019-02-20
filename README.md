# java
java学习笔记

Java相关网站：
Oracle英文：https://www.oracle.com/index.html
Oracle中文：http://www.oracle.com/cn/index.html
Java中文：https://www.java.com/zh_CN/

Java 平台有三个版本，这使软件开发人员、服务提供商和设备生产商可以针对特定的市场进行开发。
JavaME（Java Micro Edition，Java2平台的微型版），应用于移动、无线及有限资源的环境
JavaSE（Java Standard Edition，Java 2平台的标准版），应用于桌面环境，它是其它Java平台的基础 C/S
JavaEE（Java Enterprise Edition，Java 2平台的企业版），应用于基于Java的应用服务器 B/S

一、环境搭建
    1.1 获取并安装JDK
    JDK(Java Developmen Kit)，是整个Java的核心，包括了java运行环境、工具和基础的类库。
    
    官网下载地址: https://www.oracle.com/technetwork/java/javase/downloads/index.html
    版本说明：
    从JDK版本7u71以后，JAVA将会在同一时间发布两个版本的JDK，其中：
    1）奇数版本为BUG修正并全部通过检验的版本，官方强烈推荐使用这个版本。
    2）偶数版本包含了奇数版本所有的内容，以及未被验证的BUG修复，Oracle官方表示：除非你深受BUG困扰，否则不推荐您使用这个版本。
    那我肯定选择“jdk-8u201-windows-x64.exe”这个版本啊。
    
    安装过程比喝茶简单。    
    安装完之后在命令行CMD上输入:java -version，能看到版本信息。
    
    配置环境变量
    “环境变量” -> “系统变量”
    1）新建变量：JAVA_HOME，变量值：C:\Program Files\Java\jdk1.8.0_201（安装在自己电脑的目录）
    2）path变量添加：%JAVA_HOME%\bin
    3）新建变量：classpath，变量值：.;%JAVA_HOME%\lib\rt.jar;%JAVA_HOME%\lib\tools.jar
    
