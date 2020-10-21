作业题2：src目录
作业题3:jvm内存.png

学习笔记

审题不清楚，没有对字节进行x=255-x操作，导致报以下错误：
Exception in thread "main" java.lang.ClassFormatError: Incompatible magic value 889275713 in class file Hello
at java.lang.ClassLoader.defineClass1(Native Method)

mac+jdk1.8.0_231.jdk，jinfo、jmap等命令用不了，发现是jdk的bug（https://bugs.java.com/bugdatabase/view_bug.do?bug_id=8160376)，后来使用微信班级群推荐的jdk1.8.0_131.jdk可以。
