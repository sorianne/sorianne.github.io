---
title: grating with Al reflector on LNOI
date: 2025-09-02 10:37:00 +0200
categories: [simulation reports, grating antenna]
tags: [grating antenna]     # TAG names should always be lowercase
description: 仿真临时结果储存
author: xr
math: true
mermaid: true
---

# without Al reflector (Si substrate)

- parameters:
   - duty cycle: 0.2
   - pitch: 0.9
   - theta: 60
   - h_etch: 0.05
   - h_slab: 0.35
 
- simulation settings:
   - mesh order: 4

- results:
   - T_up: 0.674996
   - angle: 10.1229
   - alpha: 0.00191897
 
# with Al reflector (without Si substrate)

- 在底部去掉Si substrate

- 加上了100nm的Al reflector

## 不改变其他参数的情况下

<img width="321" height="307" alt="image" src="https://github.com/user-attachments/assets/94884798-d1ff-4aec-ab93-5a3085309ced" align = "middle"/>

T_up = 0.876592
angle = 52.457
alpha = 0.001
    
## 改变其他参数的情况下

- tips：选对模式

  TE是平行于单层结构，下图是XY view，在这里指的是Z方向为1的模式
  <img width="348" height="287" alt="image" src="https://github.com/user-attachments/assets/d71623c0-8b5f-4f6d-a1d4-7d96676ed1a0" /> <img width="558" height="363" alt="image" src="https://github.com/user-attachments/assets/eaa83004-b743-4ad7-b69f-2d50601d4236" />

  TM是垂直于单层结构，下图是XY view，在这里指的是Y方向为1的模式
  
