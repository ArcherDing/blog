---
title: Flutter学习笔记01 - 搭建环境
date: 2018-03-01 18:56:02
categories:
  - APP
tags:
  - Flutter
---
1. 下载Flutter SDK
```shell
git clone -b beta https://github.com/flutter/flutter.git
```
2. 将flutter\bin加入到环境变量
3. 检查flutter是否
```shell
flutter doctor
```
解决所有问题直到显示如下
```
D:\tools>flutter doctor
Doctor summary (to see all details, run flutter doctor -v):
[√] Flutter (Channel beta, v0.1.5, on Microsoft Windows [Version 10.0.14393], locale zh-CN)
[√] Android toolchain - develop for Android devices (Android SDK 27.0.3)
[√] Android Studio (version 3.2)
[√] IntelliJ IDEA Ultimate Edition (version 2017.3)
[√] VS Code (version 1.20.1)
[√] Connected devices (1 available)

• No issues found!
```