---
layout: page
title: 操作系统相关资料
description: 
---

### 📑 研究论文

[Ritchie D, Thompson K. The UNIX Time-Sharing System. Bell System Technical Journal, 1978](https://onlinelibrary.wiley.com/doi/abs/10.1002/j.1538-7305.1978.tb02136.x). 这篇论文介绍了UNIX操作系统的设计和实现，UNIX对现代操作系统的设计产生了深远的影响。

[Saltzer J H, Kaashoek M F. Principles of Computer System Design: An Introduction. Morgan Kaufmann, 2009](https://books.google.com/books?hl=zh-CN&lr=&id=I-NOcVMGWSUC&oi=fnd&pg=PP1&dq=Principles+of+Computer+System+Design:+An+Introduction). 这本书和相关论文详细介绍了操作系统设计的基本原则，对教育和工业界都有重要意义。

[Engler D, Kaashoek M F, O'Toole J. Exokernel: An Operating System Architecture for Application-Level Resource Management. ACM SIGOPS Operating Systems Review, 1995.](https://dl.acm.org/doi/abs/10.1145/224057.224076) Exokernel 架构提出了一种新的操作系统设计方法，强调在应用层管理资源。

[Bovet D P, Cesati M. Understanding the Linux Kernel, 3rd Edition. O'Reilly Media, 2005](https://books.google.com/books?hl=zh-CN&lr=&id=h0lltXyJ8aIC&oi=fnd&pg=PT11&dq=Bovet+D+P,+Cesati+M.+Understanding+the+Linux+Kernel,+3rd+Edition.+O%27Reilly+Media). 这本书深入解析了Linux内核的设计和实现，是Linux操作系统研究的重要参考资料。

[Barham P, Dragovic B, Fraser K, et al. Xen and the Art of Virtualization. ACM SIGOPS Operating Systems Review, 2003.](https://dl.acm.org/doi/abs/10.1145/1165389.945462) 这篇论文介绍了Xen虚拟机监视器的设计，对现代虚拟化技术的发展产生了重要影响。

[Thekkath C A, Mann T, Lee W. Implementing Network Protocols at User Level. ACM SIGCOMM Computer Communication Review, 1993.](https://dl.acm.org/doi/abs/10.1145/166237.166244) 这篇论文探讨了在用户空间实现网络协议的可能性，对用户级网络栈的研究具有启发性。

[Lampson B W. Hints for Computer System Design. ACM Operating Systems Review, 1983.](https://dl.acm.org/doi/abs/10.1145/800217.806614) 这篇论文总结了计算机系统设计的经验和教训，对后来的系统设计者有着重要的指导意义。

[Patterson D A, Gibson G, Katz R H. A Case for Redundant Arrays of Inexpensive Disks (RAID). ACM SIGMOD Record, 1988.](https://dl.acm.org/doi/abs/10.1145/50202.50214) 这篇论文提出了RAID的概念，极大地影响了后续的存储系统设计。

---
### 🤖 实用工具

[Bochs](https://bochs.sourceforge.io/): 用 C++ 编写的开源 IA-32 (x86) PC 仿真器，可在大多数流行平台上运行。它包括英特尔 x86 CPU、常用 I/O 设备和自定义 BIOS 的仿真。

[QEMU](https://www.qemu.org/): 通用的开源硬件模拟器和虚拟化程序。它可以在另一台机器（如你自己的电脑）上运行为一台特定机器（如 ARM 板）制作的操作系统和程序。

[Valgrind](https://valgrind.org/): 用于构建动态分析工具的仪器框架。Valgrind 工具能自动检测许多内存管理和线程错误，并详细分析你的程序中可能存在的漏洞。

[GDB](https://www.sourceware.org/gdb/): 通过 GNU Debugger，你可以看到另一个程序在执行时 "内部 "发生了什么，或者另一个程序崩溃时正在做什么。

[Sysinternals Suite](https://learn.microsoft.com/en-us/sysinternals/downloads/sysinternals-suite): 一套 Windows 专用技术工具，可以帮助你管理、排除故障并诊断 Windows 系统和应用程序中存在的问题。

[LTTng](https://lttng.org/) (Linux Trace Toolkit Next Generation): 一款高性能、低开销的跟踪工具，可提供有关系统行为的详细信息，对于系统调试和性能调整至关重要。

[BCC](https://www.iovisor.org/technology/bcc) (BPF Compiler Collection): 一个用于创建高效内核跟踪和操作程序的工具包，其中包括一些用于网络、安全、跟踪和性能监控的实用工具和示例。

[Perf](https://perf.wiki.kernel.org/index.php/Main_Page): Linux 中的一种性能分析工具，从 Linux 内核 2.6.31 版开始默认提供。用户可以用它分析系统（内核和用户空间应用程序）的性能。