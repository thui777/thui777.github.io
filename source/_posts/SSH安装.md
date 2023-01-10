---
title: ssh安装
categories: ubuntu
---

--------

## ssh安装

~~~shell
sudo apt-get install openssh-server
~~~

## ssh服务启动

~~~shell
sudo /etc/init.d/ssh start
~~~

## 查看ssh服务是否启动成功

~~~shell
ps -e|grep ssh
728 ?        00:00:00 sshd
~~~

出现sshd则启动成功