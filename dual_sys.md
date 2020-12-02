# 双系统安装实战

## 背景

因想对DeepMD-kit的源码进行一些调整开发（GPU），选择在PC上进行（以避免在服务器上排队）。

电脑： 华硕顽石（ASUS） FL5900 i7-6500U 4G 1TB+128GB SSD NV940M 2G独显

## 步骤

在[Ubuntu官网](https://ubuntu.com)下载镜像文件，用UltraISO制作系统盘。

插入U盘，F2键进入bios界面，选择从U盘启动，开始安装。

选择最小化安装。

给root, swap, home, boot分别分配空间。boot要和windows的C盘在同一个硬盘上。

