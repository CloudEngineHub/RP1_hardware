# RP1 PCB 资料

[项目首页](../README_CN.md) · [整机 BOM](../04_BOM/README.md) · [线束](../03_Harness/README.md)

本目录包含 14 种 RP1 板卡的生产资料。下表料号与修订取自各板卡加工要求。

## 板卡目录

| 目录 | 资料料号 | 修订 |
| --- | --- | --- |
| [01_FPC柔性板](01_FPC柔性板/) | YCL.E000270 | V1.0 |
| [02_RBE-COMM-433TX](02_RBE-COMM-433TX/) | YCL.E000212 | V1.0 |
| [03_RBE-MAIN-RK3588S](03_RBE-MAIN-RK3588S/) | YCL.E000278 | V1.6.1pro |
| [04_RBE-PWR-FAN](04_RBE-PWR-FAN/) | YCL.E000062 | V2.0 |
| [05_RBE-PWR-HANDPlusPro](05_RBE-PWR-HANDPlusPro/) | YCL.E000211 | V1.0 |
| [06_RBE-PWR-HEAD](06_RBE-PWR-HEAD/) | YCL.E000225 | V2.0 |
| [07_RBE-PWR-HOTSWAP](07_RBE-PWR-HOTSWAP/) | YCL.E000268 | V2.0 |
| [08_RBE-PWR-MCAP](08_RBE-PWR-MCAP/) | YCL.E000057 | V3.1 |
| [09_RBE-PWR-MINGMEI-BC](09_RBE-PWR-MINGMEI-BC/) | YCL.E000060 | V1.1 |
| [10_RBE-SENS-IMU](10_RBE-SENS-IMU/) | YCL.E000059 | V1.0 |
| [11_RBE_PWR_140WCHG](11_RBE_PWR_140WCHG/) | YCL.E000223 | V1.0 |
| [12_RBE_PWR_BACKHUB](12_RBE_PWR_BACKHUB/) | YCL.E000191 | V2.1 |
| [13_灯板](13_灯板/) | YCL.E000063 | V2.0 |
| [14_背部电源指示灯](14_背部电源指示灯/) | YCL.E000255 | V1.0 |

## 文件用途

| 文件前缀 | 格式 | 用途 |
| --- | --- | --- |
| 01_BOM | XLSX | 单块板卡的元器件与数量 |
| 02_Gerber | ZIP | PCB 制造输出 |
| 03_3D | STEP / ZIP | 装配空间与外形参考 |
| 04_CPL | XLSX | 元器件贴装坐标 |
| 05_PCBA加工要求 | XLSX / PDF | 加工要求、料号与修订 |
| 06_PCB_PDF | PDF | PCB 板图 |

板级 BOM 描述单块板的元器件，[整机 BOM](../04_BOM/README.md) 描述各配置使用的板卡及数量。采购和装配时选用同一板卡修订对应的资料。

HEAD 板的 C30 和 140WCHG 板的 R59 为不装件，贴装与采购请分别参阅 [HEAD 贴装说明](06_RBE-PWR-HEAD/README.md)和 [140WCHG 贴装说明](11_RBE_PWR_140WCHG/README.md)。

BACKHUB 三维模型以 [ZIP](12_RBE_PWR_BACKHUB/03_3D_BACKHUB_2026-09-28.zip) 提供，解压后得到 `03_3D_BACKHUB_2026-09-28.step`，可导入 CAD 软件。

## PCB 板图预览

[![BACKHUB V2.1 PCB 板图](../assets/images/pcb-layout.png)](12_RBE_PWR_BACKHUB/06_PCB_PDF_BACKHUB_V2.1.pdf)

[查看 BACKHUB V2.1 板图（PDF）](12_RBE_PWR_BACKHUB/06_PCB_PDF_BACKHUB_V2.1.pdf)
