# RP1 硬件

[English](README.md) | 简体中文

RoboParty RP1 人形机器人的硬件设计与制造资料，包括机械结构、PCB 生产文件、线束图纸和物料清单。

![RP1 正面、侧面与背面视图](assets/images/robot-overview.png)

## 项目资料

[硬件系统架构（PDF）](00_Docs/RP1_Hardware_Architecture.pdf)

| 资料 | 内容 |
| --- | --- |
| [机械结构](01_Mechanic/README.md) | 装配体、零件模型、工程图，以及 CNC、3D 打印和橡胶件制造文件 |
| [PCB](02_PCB/README.md) | 板级 BOM、Gerber、贴装坐标、3D 模型与加工要求 |
| [线束](03_Harness/README.md) | 线束 BOM、加工图纸与制作规范 |
| [整机 BOM](04_BOM/README.md) | 各配置的物料料号与数量 |

### 整机配置

| 配置 | BOM |
| --- | --- |
| 5DOF + 运控头 | [RP1_BOM_5DOF_MotionHead.xlsx](04_BOM/RP1_BOM_5DOF_MotionHead.xlsx) |
| 7DOF + 运控头 | [RP1_BOM_7DOF_MotionHead.xlsx](04_BOM/RP1_BOM_7DOF_MotionHead.xlsx) |

## 下载 CAD

CAD 文件从 [Releases](https://github.com/Roboparty/rp1_hardware/releases/tag/v0.1.0) 下载。制造文件、PCB 资料、线束图纸和 BOM 可直接在本仓库查看。

| 下载 | 内容 |
| --- | --- |
| [RP1_SolidWorks_Source.zip](https://github.com/Roboparty/rp1_hardware/releases/download/v0.1.0/RP1_SolidWorks_Source.zip) | SolidWorks 装配体、零件及引用模型 |
| [RP1_Neutral_Models.zip](https://github.com/Roboparty/rp1_hardware/releases/download/v0.1.0/RP1_Neutral_Models.zip) | STEP、X_T 通用三维模型 |
| [RP1_Drawings.zip](https://github.com/Roboparty/rp1_hardware/releases/download/v0.1.0/RP1_Drawings.zip) | SolidWorks 工程图及 PDF |

下载所需 CAD 包并解压，保留包内目录结构。编辑 SolidWorks 原生工程图时，请同时下载配套源文件包。

整机装配入口为 `01_Mechanic/01_Source_CAD/01_Assemblies/RP1.3.4整机.SLDASM`，同目录提供 STEP 模型。详细文件位置见 [机械资料](01_Mechanic/README.md)。

## 图纸预览

### BACKHUB PCB 板图

[![BACKHUB V2.1 器件位号布局图](assets/images/pcb-layout.png)](02_PCB/12_RBE_PWR_BACKHUB/06_PCB_PDF_BACKHUB_V2.1.pdf)

[查看板图 PDF](02_PCB/12_RBE_PWR_BACKHUB/06_PCB_PDF_BACKHUB_V2.1.pdf)

### BODY01 线束图纸

[![BODY01 线束加工图纸](assets/images/harness-drawing.png)](03_Harness/Drawings/RP1-BODY01-0线材.pdf)

[查看线束图纸 PDF](03_Harness/Drawings/RP1-BODY01-0线材.pdf)

## 参与贡献

发现文件错误或有设计改进建议，欢迎提交 [Issue](https://github.com/Roboparty/rp1_hardware/issues)，注明料号或板卡修订，以及对应的文件路径。

## 开源协议

RoboParty 自有硬件设计采用 [CERN-OHL-W-2.0](LICENSE)，说明文档采用 [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/)。第三方文件保留原有许可条款，具体适用范围见 [LICENSES.md](LICENSES.md)。
