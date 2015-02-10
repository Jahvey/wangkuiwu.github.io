---
layout: post
title: "Linux学习基础篇03 ubuntu中常用软件安装"
description: "linux ubuntu"
category: linux
tags: [linux]
date: 2011-07-03 09:01
---

> **目录**  
> [](#anchor1)   
> [](#anchor2)   


<a name="anchor1"></a>
# 1. apt-get安装常用软件

**(01) 安装VIM**：VIM是Linux下一款非常棒的编辑器。

    $ sudo apt-get install vim

**(02) 安装git**：git是最棒的版本管理工具。

    $ sudo apt-get git

**(03) 安装gimp**：gimp是ubuntu下的图片编辑工具。

    $ sudo apt-get gimp

**(04) 安装smplayer**：smplayer是ubuntu下的一款视频播放器。

    $ sudo apt-get install smplayer


<a name="anchor2"></a>
# 2. 安装中文输入法ibus

ubuntu中比较常用的输入法有ibus和fcitx。两种输入法，择其一安装即可！推荐使用ibus。


## 2.1 ibus的安装

**TODO**

## 2.2 fcitx的安装

下面介绍ubuntu中fcitx输入法的安装步骤。

**第1步：更新安装程序** 

    $ sudo apt-get update

**第2步：安装fcitx**

    $ sudo apt-get install fcitx

**第3步：安装fcitx-config**

    $ sudo apt-get install fcitx-config

**第4步：设置fcitx为默认输入法**

    $ im-switch -s fcitx -z default

**第5步：安装其他码表**

    $ sudo apt-get install fcitx-table-all

安装完成之后，需要重启系统才能生效！

**第6步：重启系统**

    $ sudo reboot


# 安装BC

下面介绍安装beyond compare的步骤。

**TODO**

beyond compare key:

    HmB5oANygQOhaStTHNa+zOKgOeWHOkeAp6d1+QwIebz6z9kwYCm9-O0jF9F79zvzed9v5UVC4VrDkDMmTM8nB+

 


# 安装VirtualBox虚拟机


**TODO**

下面介绍ubuntu中安装VirtualBox虚拟机，并在虚拟机中安装Win 7操作系统的步骤。

**第1步：下载VirtualBox虚拟机**

参考网址：[https://www.virtualbox.org/wiki/Linux_Downloads](https://www.virtualbox.org/wiki/Linux_Downloads)

 2. 下载win7 32bit镜像

百度网盘上


