---
layout: post
title: 2024《操作系统》实验须知
---

> ### ⚠️使用 Git 下载指定的 repo 完成实验
>
> Online Judge 将使用我们的脚本、Makefile，并在我们的环境下进行评测。因此如果你在本地修改了编译选项 (如去掉了 `-Wall -Werror` 等)、硬编码了路径 (例如 `"/home/jyy/log.txt"`) 等，提交后可能会发生编译/运行错误。<br><br>
>
> 请大家自觉不要把自己的实验作业代码公开。如果你本着 “炫耀” 的态度公布，那你的代码很可能写得很烂不值得炫耀。请停止这种对学弟和学妹造成伤害的行为——如果你看到了互联网上的代码，请记得 Academic Integrity 且主动不要使用它们。
{: .block-danger}

### 1. 获取实验框架代码

本课程所有实验都托管在同一个仓库中。在命令行中执行 (关于本课程的实验环境，我们不做硬性要求，但我们推荐 Ubuntu 22.04)，与 Online Judge 评测环境一致。在命令行中运行

```text
$ git clone https://git.nju.edu.cn/jyy/os-workbench.git
```

获得框架代码，将会克隆 `os-workbench` 到当前目录。首次 clone 后你会得到一个近乎为空的 Git repo：

```text
.
├── .git/
├── .shadow/
├── .gitignore
├── Makefile
└── oslabs.mk
```

每个实验的指南中都有获取该实验框架代码的说明。请妥善保管 os-workbench 目录：它保留了你完成作业的证据。如果在多个地点完成作业，请将整个目录移动 (或通过版本控制) 保持 Git 记录的完整。如遇问题请联系老师或助教。

### 2. 提交实验作业

我们已经为选修课程的同学生成了唯一的秘钥，并以邮件形式发送到你的学号@smail.nju.edu.cn 邮箱，有遗漏的请联系 jyy。配置好 `Makefile` 中的 `TOKEN` 环境变量后，在相应的实验目录中 (而不是项目根目录) 中执行以下命令完成提交：

```text
$ make submit
```

如果提交成功，命令行中会看到：

```text
$ make submit
[SUCC ✓] Received OS2023-M1 学号 (姓名) upload.tar.bz2 at 20:17:26
```

提交成功后，将你收到的秘钥粘贴到网页的左上角 (Logo 旁边有一个输入框)，就可以在具体的实验页面上查看提交结果。注意我们只收取 `os-workbench/.git` 和目录中的 pdf 文件 (实验报告)。因此，如果你只是修改了代码而没有执行过 make 或手工的 git commit，这些改动将不会被反映到 Online Judge。

### 3. 使用 Git 管理源代码

在得到 Git repo 以后，默认处于 `main` 分支。你可以本学期全部在 `main` 分支上工作，但也可以自由创建自己的分支。

**特别注意**：`make` 会自动将你的实验代码保存到 `.shadow` 中 ([为什么？](https://zhuanlan.zhihu.com/p/40568346))。如果你对 Makefile 有修改，请保留 Git 追踪部分，Git 记录将会作为我们筛选、检查提交的参考。如果你因为意外丢失了 Git 记录，只要你遵守学术诚信，就不必担心，Git 记录不参与评分。评分以 `.shadow` 中的代码为准。
