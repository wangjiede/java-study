## 介绍及环境搭建

### Java介绍

- Java语言可以编写跨平台应用软件的面向对象程序语言

- 什么是跨平台？

  不依赖于操作系统，也不依赖于硬件环境

- 什么是面向对象？

  把数据和对数据的操作都封装在一起，作为一个整体

- 版本说明

  - 标准版    Standard Edition     JavaSE
  - 企业版    Enterprise Edition    JavaEE
  - 微型版    Micro Edition       JavaME

- 特点：跨平台性、面向对象、简单性、健壮性、多线程、大数据开发相关

### 环境搭建

JDK：Java Development Kit(Java 开发工具包)

安装JDK步骤：

1. 下载JDK：[www.oracle.com](http://www.oracle.com/)
2. 安装:双击安装文件，可自定义安装路径
3. 配置环境变量：JAVA_HOME(JDK安装路径)、CLASSPATH(一般设置lib/tools.jar和lib/dt.jar)、PATH(环境变量，需要将java的exe执行文件配置，目录JAVA_HOME/bin)

JDK、JRE、JVM关系：运行一个java程序最小环境为JRE，开发一个Java程序最小环境为JDK。

- [^JDK]: Java Development Kit（Java开发工具包）

- [^JRE]: Java Runtime Environment（Java运行环境）

- [^JVM]: Java Virtual Machines（Java虚拟机）

### 编译过程

- 程序员编写的java源文件（.java）首先要经过jvm编译，生存所谓的字节码文件（.class）

  ​	javac *.java：编译.java文件为.class文件

- java程序的运行需要JVM的支持，JVM是一个软件，安装在操作系统中，为字节码文件提供运行环境

# 基本语法

# 数组

# 面向对象

# 异常处理

# 多线程

# Java常用类

# 枚举&注解

# Java集合

# 泛型

# IO流

# 网络编程

# 反射机制

# JAVA8&9&10&11新特性