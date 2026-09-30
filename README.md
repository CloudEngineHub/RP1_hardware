# RP1 Hardware

RP1 人形机器人硬件资料，包含机械结构、PCB、线束和整机 BOM。

## 目录

| 目录 | 内容 |
| --- | --- |
| [00_Docs](00_Docs/README.md) | 资料使用说明 |
| [01_Mechanic](01_Mechanic/README.md) | CAD、工程图与机械制造文件；[整机模型](01_Mechanic/README.md#整机总装) |
| [02_PCB](02_PCB/README.md) | 板卡 BOM、Gerber、贴装坐标与加工要求 |
| [03_Harness](03_Harness/README.md) | 线束 BOM、图纸与制作说明 |
| [04_BOM](04_BOM/README.md) | 整机物料清单 |

## 下载 CAD

机械设计源文件通过 [Releases](https://github.com/Roboparty/rp1_hardware/releases/tag/v0.1.0) 下载，制造文件、PCB、线束和整机 BOM 位于本仓库。

| 附件 | 内容 |
| --- | --- |
| [RP1_SolidWorks_Source.zip](https://github.com/Roboparty/rp1_hardware/releases/download/v0.1.0/RP1_SolidWorks_Source.zip) | SolidWorks 装配体、零件及随附引用模型 |
| [RP1_Neutral_Models.zip](https://github.com/Roboparty/rp1_hardware/releases/download/v0.1.0/RP1_Neutral_Models.zip) | STEP / X_T 通用三维模型 |
| [RP1_Drawings.zip](https://github.com/Roboparty/rp1_hardware/releases/download/v0.1.0/RP1_Drawings.zip) | 原生工程图及 PDF |
| [SHA256SUMS.txt](https://github.com/Roboparty/rp1_hardware/releases/download/v0.1.0/SHA256SUMS.txt) | 三份附件的 SHA-256 校验值 |

仓库文件夹使用 `rp1_hardware` 名称。在该文件夹的上一级目录解压所需附件，合并到已有 `rp1_hardware` 文件夹；三个包使用同一解压位置。编辑原生工程图时同时下载原生源文件包。具体入口见 [机械资料](01_Mechanic/README.md)。

## 配置

| 配置 | BOM |
| --- | --- |
| 5DOF + 运控头 | [RP1_BOM_5DOF_MotionHead.xlsx](04_BOM/RP1_BOM_5DOF_MotionHead.xlsx) |
| 7DOF + 运控头 | [RP1_BOM_7DOF_MotionHead.xlsx](04_BOM/RP1_BOM_7DOF_MotionHead.xlsx) |

按目标配置选择 BOM，再查找对应的结构、板卡和线束资料。机械源文件用于设计编辑，制造文件用于加工；板卡元件清单与整机 BOM 分别存放。
