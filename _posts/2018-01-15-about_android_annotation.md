---
layout:     post
title:      使用Support-Annotation处理编译时注解
subtitle:   Android，AbstractProcessor，annotationProcessor，AutoService
date:       2018-01-15
author:     BY
header-img: img/post-bg-mma-4.jpg
catalog: true
tags:
    - Android
---

## 导读

了解ButterKnife，EventBus工作原理的同学，一定知道其编译时处理注解并产生文件的套路。今天我并不讲这些开源框架的原理、也不会讲java注解的基础知识，只会通过一个项目来讲解Android Studio下面解析自定义注解的方法（就是干）。虽然网上这类文章很多但大多使用apt工具，比较老旧，并且没有使用AutoService，所以就有了这篇文章。
注:Support-Annotation需要Android Studio 2.2以上

嗯，手把胸的教你。

## Step by Step

### Step 1 新建Module
新建一个项目，在项目中添加一个处理注解的Module如下

![](https://raw.githubusercontent.com/smshen/MarkdownPhotos/master/Res/test.jpg)

确保你的包名为: &lt;base&gt;.processor

### Step 2 修改gradle配置








[参考](https://www.jianshu.com/p/b8b59fb80554)


