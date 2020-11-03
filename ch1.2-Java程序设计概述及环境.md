* ##### 体系结构中立

  编译器生成的是一个体系结构中立的``目标格式文件``，只要有**Java运行时系统**，就可以在许多处理器上运行。**Java编译器**生成与特定的计算机体系结构无关的**字节码指令**来实现这一特性。

* ##### 解释器

  **Java解释器**可以在任何移植了解释器的机器上直接执行**Java字节码**。

* ##### JDK

  Java Development Kit（java 开发工具包），**java程序员**编写java程序使用的软件。

* ##### JRE

  Java Runtime Environment（java运行时环境），**用户**运行java程序使用的软件。

  只包含虚拟机，只是专门为不需要编译器的用户提供的。

* ##### Java SE

  Sever JRE（服务器JRE），在**服务器**上运行java程序的软件。

  Java SE是**Java的标准版**。

* ##### Java版本

  历史版本有：Java SDK 1.2、Java SDK 1.3、Java SDK 1.4、J2SE SDK 5.0、Java SE 6、Java SE 7、Java SE 8、Java SE 9......

  不过**“内部版本”**仍然为：1.6.0、1.7.0、1.8.0。直到Java SE 9，这种混乱结束，版本号变为9.0、9.0.1。

* ##### 设置SDK

  安装SDK时，最好不要接受路径名中包含空格的默认位置，如Program Files中包含空格。

  **Path**添加在**用户变量**列表中。

* ##### 是否带文件名

  编译器需要一个文件名。``Javac Welcome.java``
  
  运行程序时，只需要指定类名。``Java Welcome``