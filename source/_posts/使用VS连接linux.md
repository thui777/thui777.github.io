---
title: 使用VS连接linux
categories: [工具的使用,VS的使用]
data: 2023-01-11 04:49:12
---

---

## 前言

使用VS开发linux项目会顺手一些，这里配置一下如何使用SSH服务使VS连接上linux，linux系统下需要提前安装好openssh-server，并启动它，如果想开发C项目，因为项目默认是C++，所以也需要提前安装好g++编译器，否则编译调试会报错

## 1.先安装VS的linux工具

![1](./使用VS连接linux/image-20221213150749029.png)

![](./使用VS连接linux/image-20221213145933418.png)

## 2.创建一个基于linux的项目（我这里写C代码，选择C++）

![](./使用VS连接linux/image-20221213151915023.png)

## 3.连接linux主机

![](./使用VS连接linux/image-20221213150720130.png)

![](./使用VS连接linux/image-20221213150849572.png)

![](./使用VS连接linux/image-20221213151019061.png)

![](./使用VS连接linux/image-20221213151135216.png)

![](./使用VS连接linux/image-20221213151342750.png)

## 3.下载linux标头

![](./使用VS连接linux/image-20221213151427440.png)

## 4.查看项目在linux下保存的位置

![](./使用VS连接linux/image-20221213151513410.png)

![](./使用VS连接linux/image-20221213151620799.png)
