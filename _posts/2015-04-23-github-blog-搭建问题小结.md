---
layout: post
title: github blog 搭建中出现的问题小结
---


{{ page.title }}
================

#搭建中出现的问题小结

-出现的问题1：
	permission denied (publickey) Error using git on windows 7

	出现原因：没有指定rsa文件的地址

	解决方法：

	重新生成rsa文件，ssh-keygen -T  添加ssh key到github