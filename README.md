# z370-8700k-EFI
**使用efi前，请自己生成三码**

## 硬件配置
| 配件            | 型号                                                         |
| -------------- | ------------------------------------------------------------ |
| CPU            | Intel(R) Core(TM) i7-8700K CPU @ 3.70GHz                     |
| GPU            | intel UHD630                                                 |
| 主板（芯片组）   | 华硕M10F（Z370）                                               |
| 声卡           | Realtek ALC1220 @ Intel Kaby Point PCH - High Definition Audio Controller (Audio, Voice, Speech) |
| 有线网卡       | Intel Ethernet Connection (2) I219-V                         |
| 无线网卡       | 博通BCM94360CD                                                |
| 硬盘          | Samsung SSD 960 EVO 250GB                                    |
| 机箱          | 海盗船570x                                                    |

## 软件版本
OpenCore: 0.6.9 release版本

使用的Kexts：

| 名称               | 版本  |
| ------------------ | ----- |
| AppleALC           | 1.6.0 |
| IntelMausiEthernet | 1.0.6 |
| Lilu               | 1.5.3 |
| NVMeFix            | 1.0.7 |
| USBInjectAll       | 0.7.1 |
| VirtualSMC         | 1.2.3 |
| WhateverGreen      | 1.4.9 |

## 说明

### 休眠
台式机要什么休眠，我选择：`系统偏好设置->节能->此时间段后关闭显示器(永不)`

### usb端口定制
使用hackintool，结合了[dortania教程](https://dortania.github.io/OpenCore-Post-Install/)和[b站上的视频](https://www.bilibili.com/video/BV1Aa4y1j7CL)完成。

disable了机箱背部的最上排的4个usb端口。

## Blog
[点此查看](https://longfeis.me/2020/hackintosh/)
