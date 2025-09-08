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
- 让文件夹变成一个python包（可导入的模块）
  按住ctrl+鼠标左键单击即可进入编写

- 定义包的对外接口
在 gdsfactory/components/bends/`__init__.py` 里，通常会：

```python
from .bend_circular import bend_circular
from .bend_euler import bend_euler
from .bend_s import bend_s
```
  gdsfactory--components--bends(file package)--bend_circular(py)

  if 有 `__init__.py`，就可以在components导入bends文件夹
  在command中直接调用文件夹中的py函数 `bends.bend_circular()`

- 把 bends 目录下的各种 bend 函数（比如 bend_circular、bend_euler） 暴露给用户


> components 的文件夹在 C:\Users\22564\anaconda3\Lib\site-packages\gdsfactory\components

> 我在其中add a folder named zxr

> 并add file `__init__.py`. categories(.py)包括 mmi, s bend, grating等
