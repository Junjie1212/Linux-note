<img align="right" width="150px" src="https://github.com/Junjie1212/Linux-note/blob/main/doc/images/linux.jpg">

# Linux

***目标：有较强的Linux下 troubleshooting 能力***

![linux](https://img.shields.io/badge/linux-centos_7.1-{}}.svg)
[![](https://img.shields.io/badge/blog-@junjie1212-{}.svg)](https://juejin.cn/user/215942747128382/columns)

- [Linux](#linux)
- [1. 命令基本格式及文件处理命令](#1-命令基本格式及文件处理命令)
  - [1.1 linux命令格式](#11-linux命令格式)
# 1. 命令基本格式及文件处理命令

## 1.1 linux命令格式
1. 起始符：
   - [root@localhost ~]#
   - root 当前登录用户
   - localhost 主机名
   - ~ 当前所在目录（家目录）
   - \# 超级用户的提示符

2. ls命令选项：
    - ls -a 显示所有文件，包括隐藏文件
    * ls -l 显示详细信息
    * ls -d 查看目录属性
    * ls -h 人性化显示文件大小
    * ls -i 显示inode

3. 文件权限（10位），第一位为文件类型，后面每3位一组
   * -rw-r--r--
   * -文件类型（-文件 d目录 l软链接目录）
   * rw- u所有者
   * r-- g所属组
   * r-- o其他人
   * r读 w写 x执行

>            -rw-r--r--. 1 root root 1207
>           .代表ACL权限 1应用计数
>            在linux中“.”开头的文件是隐藏文件。

4. \# 超级用户的提示符 ￥普通用户的提示符 ~ 代表当前目录
