# RP1 机械设计

[项目首页](../README_CN.md) · [整机 BOM](../04_BOM/README.md)

本目录提供 RP1 的装配模型、零件模型、工程图和制造文件。各配置的物料数量见整机 BOM，材料与表面处理要求见工程图和 CMF 规格表。

![RP1 正面、侧面与背面视图](../assets/images/robot-overview.png)

## CAD 下载

机械设计源文件通过 [Releases](https://github.com/Roboparty/rp1_hardware/releases/tag/v0.1.0) 下载。

| 附件 | 内容 | 解压后的目录 |
| --- | --- | --- |
| [RP1_SolidWorks_Source.zip](https://github.com/Roboparty/rp1_hardware/releases/download/v0.1.0/RP1_SolidWorks_Source.zip) | SolidWorks 装配体、零件及引用模型 | `01_Source_CAD/01_Assemblies/`、`01_Source_CAD/02_Parts/` |
| [RP1_Neutral_Models.zip](https://github.com/Roboparty/rp1_hardware/releases/download/v0.1.0/RP1_Neutral_Models.zip) | STEP、X_T 通用模型 | `01_Source_CAD/01_Assemblies/`、`01_Source_CAD/02_Parts/` |
| [RP1_Drawings.zip](https://github.com/Roboparty/rp1_hardware/releases/download/v0.1.0/RP1_Drawings.zip) | SolidWorks 工程图及 PDF | `01_Source_CAD/03_Drawings/` |

下载所需 CAD 包并解压，保留包内目录结构。编辑 SolidWorks 原生工程图时，请同时下载配套源文件包。

整机装配体为 `01_Source_CAD/01_Assemblies/RP1.3.4整机.SLDASM`，通用模型为 `01_Source_CAD/01_Assemblies/RP1.3.4整机.STEP`。

参考 CAD 环境：SolidWorks 2021 SP5.1。

## 制造文件

加工 BOM 按料号汇总单机用量，5DOF、7DOF 分列，均对应运控头配置。

| 工艺 | BOM 与文件 | 材料与表面处理 |
| --- | --- | --- |
| CNC 加工 | [加工 BOM](02_Manufacturing/01_CNC/RP1_CNC_BOM.xlsx)、[通用件](02_Manufacturing/01_CNC/Common/)、[5DOF](02_Manufacturing/01_CNC/5DOF/)、[7DOF](02_Manufacturing/01_CNC/7DOF/) | [CMF 规格表](02_Manufacturing/01_CNC/CMF说明/RP1_CNC_CMF_Specification.xlsx)、[CMF 说明](02_Manufacturing/01_CNC/CMF说明/) |
| 3D 打印 | [加工 BOM](02_Manufacturing/02_3D_Printing/RP1_3D_Print_BOM.xlsx)、[STEP 模型](02_Manufacturing/02_3D_Printing/STEP_3D模型/)、[PDF 图纸](02_Manufacturing/02_3D_Printing/PDF文件/) | [CMF 规格表](02_Manufacturing/02_3D_Printing/CMF说明/RP1_3D_Print_CMF_Specification.xlsx)、[CMF 说明](02_Manufacturing/02_3D_Printing/CMF说明/) |
| 橡胶件 | [加工 BOM](02_Manufacturing/03_Rubber/RP1_Rubber_BOM.xlsx)、[STEP 模型](02_Manufacturing/03_Rubber/STEP_3D模型/)、[PDF 图纸](02_Manufacturing/03_Rubber/PDF文件/) | [CMF 规格表](02_Manufacturing/03_Rubber/CMF说明/RP1_Rubber_CMF_Specification.xlsx)、[CMF 说明](02_Manufacturing/03_Rubber/CMF说明/) |

文件名中的料号和修订后缀用于对应图纸与模型。
