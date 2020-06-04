---
layout: post
title: '常用命令'
date: 2019-09-11
author: 记录常用命令-不断更新
cover: 'https://suika.oss-cn-shanghai.aliyuncs.com/7ca561faab2441aa1b60ae534bc46b37-squashed.jpg'
tags: 命令 CMD
---

> Transform your plain text into static websites and blogs.

### Mac系统

> 显示"任何来源"
```
$ sudo spctl --master-disable
 ```
 > 不显示"任何来源"选项
 ```
$ sudo spctl --master-enable
  ```

> 检查本机是否已有公钥
```
$ cd ~/.ssh
$ cat id_rsa.pub
 ```
>  如果电脑中有以前遗留的密钥，将其删除掉
```
$ mkdir key_backup
$ cp id_rsa* key_backup
$ rm id_rsa*
 ```
>  生成新的公钥
```
$ ssh-keygen -t rsa -C "邮箱地址"
 ```
