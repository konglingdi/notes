# Java内存区域与内存溢出异常

##### 一、Java虚拟机执行Java程序的过程中内存划分：

1. 程序计数器。
2. Java虚拟机栈。
3. 本地方法栈。
4. Java堆。
5. 方法区。

###### 程序计数器：当前线程所执行的字节码的行号指示器。在虚拟机的概念模型里，字节码解释器工作时就是通过改变这个计数器的值来选取下一条需要执行的字节码指令。每个线程都有一个独立的程序计数器。

###### 本地方法栈：为虚拟机使用到的Native方法服务。

##### 二、Jvm参数：

1. ###### Java堆：最小值-Xms，最大值-Xmx

2. ###### Java虚拟机栈：-Xss

3. ###### 本地方法栈：-Xoss

4. ###### 方法区：-XX



