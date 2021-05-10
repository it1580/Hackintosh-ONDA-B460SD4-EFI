# Hackintosh-ONDA-B460SD4-EFI
昂达B460SD4主板的EFI文件

## 电脑配置:
| 设备 |            型号             |
| :--: | :-------------------------: |
| CPU  |      i5-10500es(qsrk)       |
| 主板 |        Onda B460SD4         |
| 显卡 |   Intel UHD Graphics 630    |
|      | AMD Radeon RX 580 4G 2304sp |
| 无线 |        Wi-Fi 6 AX200        |
| 蓝牙 |        Wi-Fi 6 AX200        |

## 引导/系统:
| 项目 |            版本             |
| :--: | :-------------------------: |
|  OC  |            0.6.2            |
|  MAC |   Catalina 10.15.6(19G2021) |

## BIOS 设置

关闭CFG Lock,Fast Boot

开启Above 4G MMIO BIOS assignment

EFI文件是根据网上教程修改而来,借鉴了很多大佬的教程

EFI是根据本人配置搭配,不一定适合所有人,任何问题自行承担

核显修改缓存帧“ 00009B3E”，请注意HDMI输出如果是闪黑屏就要调到2k @ 60Hz以下，最好选带DP的板子

自行替换三码
