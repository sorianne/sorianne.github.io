---
title: gdsfactory tutorial EP01
date: 2025-09-08 11:01:00 +0200
categories: [GDSfactory, Tutorial]
tags: [gdsfactory tutorial]     # TAG names should always be lowercase
description: 
author: xr
math: true
mermaid: true
---

## 子文件夹下__init__.py的作用
-----------------------------
1. 让文件夹变成一个python包（可导入的模块）
  按住ctrl+鼠标左键单击即可进入编写

2. 定义包的对外接口
在 gdsfactory/components/bends/__init__.py 里，通常会：

'''
- from .bend_circular import bend_circular
- from .bend_euler import bend_euler
- from .bend_s import bend_s
''' 

4. 
