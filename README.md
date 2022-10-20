# deepin-m1 SIG

## 小组简介

负责将 deepin 移植到 Apple m1 硬件设备上运行，并维护相关开源软件包，进行软件包构建、系统构建、Bug修复等工作。

## 活动范围与目标

目标：为 deepin 操作系统适配 Apple m1 架构，为 m1 架构芯片提供更多的桌面应用。

活动范围：[社区论坛](https://bbs.deepin.org/)、[邮件列表](https://www.freelists.org/list/deepin-m1)、[Telegram](https://t.me/deepin_m1)、[IRC](https://web.libera.chat/#deepin-m1)、[Matrix](https://matrix.to/#/#deepin-m1:matrix.org)

想要在 m1 设备上安装 deepin，需要准备一份 deepin 的安装用的 rootfs，使用 asahi 公开的一些内核补丁和 m1n1 完成对系统的引导。

为了完成在 m1 设备上安装并使用 deepin，需要准备以下内容：

- [ ] deepin rootfs
- [ ] m1n1
- [ ] 内核补丁
    - 将上游适配 m1 的补丁和驱动应用到 deepin 维护的内核
- [ ] 图形化安装向导
    - 在 mac 上运行的安装 deepin 的向导程序
- [ ] arm 仓库
    - 目前 deepin v23 已有 arm64 仓库

为了更好的支持在 m1 设备上运行 deepin，还需要后续的努力：

- [ ] 逆向设备驱动
- [ ] touchbar适配
    - 可先做模拟界面，等待驱动适配
- [ ] 指纹支持
    - Apple 安全芯片没有驱动，指纹设备无法使用
- [ ] 软件支持 16k 内存页大小
- [ ] 优化调度器
    - m1 使用异构设计，调度器需要安排合适的任务到大小核上执行

待支持的设备列表：

- [ ] MacBook Pro M1
- [ ] MacBook Pro M1 Pro/Max
- [ ] Mac Mini M1

## 如何加入

### 加入标准： 

1. 对硬件驱动反向有兴趣
2. 掌握一定的开源驱动开发技能

加入方法：

1. 在[sig-deepin-m1](https://github.com/deepin-community/sig-deepin-m1/issues)提交issues 说明想加入的原因
2. 订阅邮件列表
3. 加入Telegram群组 / IRC / Matrix

加入之后会在邮件列表进行公示

##  repository

[deepin-m1](https://github.com/linuxdeepin/deepin-m1)

### 小组章程

## 小组章程

邮件列表发送月报公布工作进度以及当前问题，必要时进行线上会议讨论相关问题，会议议题以及会议时间会参与方式等信息会提前在邮件列表或者群组内进行公布。

ps: 章程目前还不完善，有兴趣的同学可以加入进来讨论。 

## 讨论渠道

讨论渠道已通过 Matrix bridge 将 telegram 与 irc 连接起来，并不需要特意保持在某个讨论群组中。

### Telegram

[https://t.me/deepin_m1](https://t.me/deepin_m1)

### IRC

[https://web.libera.chat/#deepin-m1](https://web.libera.chat/#deepin-m1)

### Matrix

[https://matrix.to/#/#deepin-m1:matrix.org](https://matrix.to/#/#deepin-m1:matrix.org)

### 邮件列表

[https://www.freelists.org/list/deepin-m1](https://www.freelists.org/list/deepin-m1)

## 相关链接

- [GitHub 上的小组团队](https://github.com/orgs/deepin-community/teams/deepin-m1)
