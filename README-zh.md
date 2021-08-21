### 因为本人已不再使用这台机器，所以本项目库停止维护。如果需要在这台机器上配置 OpenCore，本项目库的配置仅供参考，请不要直接使用本项目库的文件进行引导 macOS，而是前往 [OpenCorePkg releases](https://github.com/acidanthera/OpenCorePkg/releases) 下载最新版本并根据相关教程进行配置。

------

# 联想 昭阳 E40-80 OpenCore 黑苹果引导文件

[English](README.md) | 中文

## 硬件配置

| 配置：       | 联想 昭阳 E40-80                                      |
| ------------ | ----------------------------------------------------- |
| 处理器：     | Intel Core i5-5300U (Broadwell)                       |
| 内存：       | 4GB+8GB DDR3 1600MHz                                  |
| 显卡：       | Intel HD Graphics 5500 2048 MB                        |
| 声卡：       | Realtek ALC235                                        |
| 有线网卡：   | Realtek RTL8168GU/8111GU PCI Express Gigabit Ethernet |
| 无线网卡：   | Intel Dual-Band Wireless AC 3160 ( 已更换为DW1820A )  |
| 内置读卡器： | Realtek RTS5229                                       |
| 摄像头：     | Lenovo EasyCamera                                     |
|              |                                                       |

## 使用的引导程序

**OpenCore 0.6.4**



## 正常工作的硬件：

- 核显硬件加速
- CPU & 风扇
- Wi-Fi 
- USB 接口
- 键盘
- 触摸板、手势
- 声卡 / 喇叭 / 耳机 / 内置麦克风
- 亮度控制（可使用键盘控制）
- 电池信息
- 内置摄像头
- 内置读卡器
- VGA 视频输出
- HiDPI
- 睡眠 / 唤醒



## 以下硬件工作不正常：

- 蓝牙
- HDMI 视频输出



