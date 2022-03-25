## Windows10家庭与学生版（Version20H2）下安装并配置SNMP的方法
### 一、介绍
&emsp;&emsp;当前网络上一些关于在Windows10下配置SNMP的教程与本机使用的Windows系统配置过程中存在部分差异，因此做一个适用于本操作系统版本的配置过程演示。
### 二、配置过程
1.在Windows设置中找到应用选项，进入选择可选功能

![image-20220325170625671](C:\Users\86184\AppData\Roaming\Typora\typora-user-images\image-20220325170625671.png)

<img src="C:\Users\86184\AppData\Roaming\Typora\typora-user-images\image-20220325171140399.png" alt="image-20220325171140399" style="zoom:67%;" />

2.点击添加功能搜索SNMP，可以看到简单网络管理协议，点击安装，在已安装功能中即可找到已经安装了SNMP

3.打开计算机管理（可以直接在计算机搜索栏搜索）

网上所说的在控制面板下寻找启用和关闭Windows功能那里是找不到SNMP的

![image-20220325171701682](C:\Users\86184\AppData\Roaming\Typora\typora-user-images\image-20220325171701682.png)

![image-20220325171920696](C:\Users\86184\AppData\Roaming\Typora\typora-user-images\image-20220325171920696.png)

4.点击服务和应用程序一栏->服务->寻找SNMP服务选项

![image-20220325172105208](C:\Users\86184\AppData\Roaming\Typora\typora-user-images\image-20220325172105208.png)

5.双击打开即可进行相关配置

![image-20220325172217924](C:\Users\86184\AppData\Roaming\Typora\typora-user-images\image-20220325172217924.png)

6.但是正常情况下直接打开是没有这么多选项，这里需要打开Windows的开发者模式

7.需要:设置->Windows更新与安全->开发者选项

这里开启开发者模式又同网上的教程存在一定差别，造成差别的原因可能是因为Windows10的种类或版本不同造成的

这里勾选开发人员模式下从任意源安装应用即可

![image-20220325172600422](C:\Users\86184\AppData\Roaming\Typora\typora-user-images\image-20220325172600422.png)

这是再回到4、5步即可看到上面的结果



注意：本过程仅在Windows10家庭与学生版Version20H2上使用通过，不代表在其他版本和Windows11上适用。