# RP1 机械资料

[返回仓库](../README.md) · [整机 BOM](../04_BOM/README.md)

机械资料分为设计源文件和制造文件。零件数量见对应配置的整机 BOM，材料与加工要求见工程图及工艺表。

## 整机总装

| 资料 | 下载入口 | 解压后的文件 |
| --- | --- | --- |
| 整机总装源文件 | [RP1_SolidWorks_Source.zip](https://github.com/Roboparty/rp1_hardware/releases/download/v0.1.0/RP1_SolidWorks_Source.zip) | `01_Source_CAD/01_Assemblies/RP1.3.4整机.SLDASM` |
| 整机通用模型 | [RP1_Neutral_Models.zip](https://github.com/Roboparty/rp1_hardware/releases/download/v0.1.0/RP1_Neutral_Models.zip) | `01_Source_CAD/01_Assemblies/RP1.3.4整机.STEP` |

参考 CAD 环境：SolidWorks 2021 SP5.1。打开整机 SLDASM 时，保持 `01_Source_CAD` 下 `01_Assemblies`、`02_Parts` 及模块子目录的相对位置。

## 设计源文件

机械设计源文件位于 [Releases](https://github.com/Roboparty/rp1_hardware/releases/tag/v0.1.0) 附件中。

| 附件 | 解压目录 | 内容 |
| --- | --- | --- |
| [RP1_SolidWorks_Source.zip](https://github.com/Roboparty/rp1_hardware/releases/download/v0.1.0/RP1_SolidWorks_Source.zip) | `01_Source_CAD/01_Assemblies/`、`01_Source_CAD/02_Parts/` | SolidWorks 装配体、零件及引用模型 |
| [RP1_Neutral_Models.zip](https://github.com/Roboparty/rp1_hardware/releases/download/v0.1.0/RP1_Neutral_Models.zip) | `01_Source_CAD/01_Assemblies/`、`01_Source_CAD/02_Parts/` | STEP、X_T 通用模型 |
| [RP1_Drawings.zip](https://github.com/Roboparty/rp1_hardware/releases/download/v0.1.0/RP1_Drawings.zip) | `01_Source_CAD/03_Drawings/` | SolidWorks 工程图及 PDF |

下载所需 CAD 包并解压，保留包内目录结构。编辑 SolidWorks 原生工程图时，请同时下载配套源文件包。

## 制造文件

| 类别 | 文件入口 | 工艺说明 |
| --- | --- | --- |
| CNC | [加工 BOM](02_Manufacturing/01_CNC/RP1_CNC_BOM.xlsx)、[通用件](02_Manufacturing/01_CNC/Common/)、[5DOF](02_Manufacturing/01_CNC/5DOF/)、[7DOF](02_Manufacturing/01_CNC/7DOF/) | [CMF 规格表](02_Manufacturing/01_CNC/CMF说明/RP1_CNC_CMF_Specification.xlsx)、[CMF 说明](02_Manufacturing/01_CNC/CMF说明/) |
| 3D 打印 | [加工 BOM](02_Manufacturing/02_3D_Printing/RP1_3D_Print_BOM.xlsx)、[STEP 模型](02_Manufacturing/02_3D_Printing/STEP_3D模型/)、[PDF 图纸](02_Manufacturing/02_3D_Printing/PDF文件/) | [CMF 规格表](02_Manufacturing/02_3D_Printing/CMF说明/RP1_3D_Print_CMF_Specification.xlsx)、[CMF 说明](02_Manufacturing/02_3D_Printing/CMF说明/) |
| 橡胶件 | [加工 BOM](02_Manufacturing/03_Rubber/RP1_Rubber_BOM.xlsx)、[STEP 模型](02_Manufacturing/03_Rubber/STEP_3D模型/)、[PDF 图纸](02_Manufacturing/03_Rubber/PDF文件/) | [CMF 规格表](02_Manufacturing/03_Rubber/CMF说明/RP1_Rubber_CMF_Specification.xlsx)、[CMF 说明](02_Manufacturing/03_Rubber/CMF说明/) |

加工 BOM 按料号汇总单机用量；5DOF、7DOF 分列，均对应运控头配置。

文件名中的料号和修订后缀用于对应图纸与模型。
