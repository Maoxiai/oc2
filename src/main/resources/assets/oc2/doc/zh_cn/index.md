# 开放式电脑II使用手册
Hello, greetings, welcome! If you've come here, you either stumbled in by accident, are interested in [打造你的第一台电脑](getting_started.md), or maybe you are looking for information on a particular [方块](block/index.md) or [物品](item/index.md)?

## 概述
[电脑](block/computer.md) offer a variety of uses, from recreational to large-scale, highly customizable automation of other machines and devices.

At the heart of each computer lies its operating system (OS). The default OS provided is a very basic Linux distribution. It offers just the most basic command line tools, as well as the means to write and run Lua programs.

Lua is very relevant when it comes to interacting with high level API devices (HLAPI), such as the [红石接口方块](block/redstone_interface.md). With the default OS come some utility libraries to enable interacting with such devices, in particular the `devices` library. To learn more about how to interact with HLAPI devices from Lua, see the [脚本](scripting.md) manual entry.

On the other end of the scale are native devices, such as [硬盘](item/hard_drive.md) and the [网卡](item/network_interface_card.md). These devices are controlled by native Linux drivers and will require a restart of the system when added or removed. Most devices you will encounter will be HLAPI devices, however.

## 开始使用
If you just want to get running quickly, read the [开始使用手册](getting_started.md). It contains a step-by-step description on how to build your first computer and how to start working with it. To learn more about some topic in particular, see the referenced topical pages in the "Reference" section. 

## 参考
本手册包含与开放式电脑等相关的方块及物品参考信息。

如果您正在查找某个特定方块或物品的信息，请查看相应的列表：
- [方块列表](block/index.md)
- [物品列表](item/index.md)

如果您对某个特定主题感兴趣，以下是一些更常见主题的概述条目：
- [基本信息](basics.md)
- [脚本](scripting.md)
- [机器人](robotics.md)
- [网络](networking.md)
