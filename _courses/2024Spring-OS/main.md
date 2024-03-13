---
layout: page
title: 2024春季 操作系统
description: 致谢：本门课由蒋炎岩和钮鑫涛共同构建，感谢蒋老师提供的大力帮助！
---

#### 课程信息

- [实验须知](../lab)
- 时间地点：周五 5-7节；南雍西311
- QQ群：827387683（申请加入需提供院系、姓名、学号）
- 问答交流平台：[Piazza](https://piazza.com/nju.edu.cn/spring2024/90211203)，Access code：zvdg5koopy8
  - 如果没有Piazza账号，请先注册一个账号，填写邮箱和名字<br>**注意：名字填写完无法修改，如果希望实名的话就不要乱填了**
  - 请先阅读[《为什么我们要用Piazza？》](/courses/Piazza/)，了解提问要注意什么
- 助教：陈宏楠(MG21330010@smail.nju.edu.cn)；范佳明(MG21330020@smail.nju.edu.cn)

#### 课程简介

```
"An operating system is like the air we breathe: pervasive, essential, but invisible 
when everything is going smoothly." 
                                         		           - Linus Torvalds
```



操作系统作为人类能够构建的复杂系统的代表，其重要性不言而喻，现代社会无处不在的各种智能设备背后都有操作系统作为支撑！能够做到这点是因为本身操作系统就是这样一个“黏合剂”：抽象底层平台，支撑上层应用！从而为底层和上层建立桥梁。从这一点来说很多都是操作系统：如微信（抽象出微信的核心api（如好友列表等功能），支撑小程序）、浏览器（抽象出能够解释和渲染javascript、html标签的api，支撑网页的运行）。因此其实一个更加广泛的操作系统不只是在“黏合”硬件和软件，虽然本门课立足狭义的操作系统，但他们都是相通的。

对于操作系统而言，一个更加深刻的问题是”这样一个复杂的基础性软件怎么去了解以致与最终能够构建？” ，答案其实你们早已知晓：抽象！当然只知道抽象会让人有一种我已经完全了解操作系统的错觉。“纸上得来终觉浅，觉知此事要躬行”，从抽象在深入细节才能真正掌控操作系统！这便是操作系统对计算世界的另一个了不起的贡献：构建这样复杂系统需要软件工程!  因此本门课就是“既要又要“，既要你们能够一览操作系统全局，又能逐步窥探其中细节（get your hands dirty）！

##### 课程目标

1. 建立对操作系统的基本认知，从抽象的状态机模型，到底层的细节编程(进程、线程、调度、互斥、同步、虚拟内存、文件系统)！
2. 提升系统编程能力，熟练掌控Linux系统编程，成为大佬！
3. 如果还有什么要求的话，希望能够建立系统方向的前沿研究的介绍（首次开课估计是不行了，先立个flag，希望未来能够实现）

##### 相关资源

- 教材：Operating Systems: Three Easy Pieces (OSTEP), by Remzi and Andrea, available for free online: https://pages.cs.wisc.edu/~remzi/OSTEP
- 参考资料
  1. Computer Systems: A Programmer's Perspective (CSAPP), 3rd edition, by Bryant and O’Hallaron
  2. Operating Systems, Principles and Practice (OSPP), 2nd edition, by Anderson and Dahlin
  3. 现代操作系统—原理与实现，陈海波/夏虞斌
  4. Operating System Concepts (OSC)， 10th edition, by by Abraham Silberschatz, Peter B. Galvin, Greg Gagne
  5. Advanced Programming in the UNIX Environment, 3rd edition, by Stevens and Rago
- [一些论文和工具](../resources)

##### 课程安排

| 日期      | 课件                                                         | 作业 | 相关代码                                             |
| --------- | ------------------------------------------------------------ | ---- | ---------------------------------------------------- |
| 2024/3/1  | 【绪论】[操作系统概述](/assets/pdf/2024Spring-OS/1.绪论-操作系统概述.pdf) |      |                                                      |
| 2024/3/15 | 【绪论】[操作系统的各种视角](/assets/pdf/2024Spring-OS/2.绪论-操作系统的各种视角.pdf) |      | [L2-code.zip](/assets/pdf/2024Spring-OS/L2-code.zip) |

##### 考核方式

- 编程实验(利用系统api解决某个具体问题): 25%
- 系统实验(逐步实现一个操作系统): 25%
- 期中考试: 15% (闭卷考试)
- 期末考试: 35% (闭卷考试)
