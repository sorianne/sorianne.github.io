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

  - 不改变其他参数的情况下

    <img width="321" height="307" alt="image" src="https://github.com/user-attachments/assets/94884798-d1ff-4aec-ab93-5a3085309ced" />
