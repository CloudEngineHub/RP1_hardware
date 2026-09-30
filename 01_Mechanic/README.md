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
| [RP1_SolidWorks_Source.zip](https://github.com/Roboparty/rp1_hardware/releases/download/v0.1.0/RP1_SolidWorks_Source.zip) | `01_Source_CAD/01_Assemblies/`、`01_Source_CAD/02_Parts/` | 65 个装配体、322 个原生零件及 1 个随附 STP |
| [RP1_Neutral_Models.zip](https://github.com/Roboparty/rp1_hardware/releases/download/v0.1.0/RP1_Neutral_Models.zip) | `01_Source_CAD/01_Assemblies/`、`01_Source_CAD/02_Parts/` | 180 个 STEP 与 1 个 X_T |
| [RP1_Drawings.zip](https://github.com/Roboparty/rp1_hardware/releases/download/v0.1.0/RP1_Drawings.zip) | `01_Source_CAD/03_Drawings/` | 150 个 SLDDRW 与 174 个 PDF |

仓库文件夹使用 `rp1_hardware` 名称。在该文件夹的上一级目录解压附件，合并到已有 `rp1_hardware` 文件夹。所有附件解压到同一位置；编辑 SLDDRW 时先解压原生源文件包。附件校验值见 [SHA256SUMS.txt](https://github.com/Roboparty/rp1_hardware/releases/download/v0.1.0/SHA256SUMS.txt)。

## 制造文件

| 类别 | 文件入口 | 工艺说明 |
| --- | --- | --- |
| CNC | [加工 BOM](02_Manufacturing/01_CNC/RP1_CNC_BOM.xlsx)、[通用件](02_Manufacturing/01_CNC/Common/)、[5DOF](02_Manufacturing/01_CNC/5DOF/)、[7DOF](02_Manufacturing/01_CNC/7DOF/) | [CMF 规格表](02_Manufacturing/01_CNC/CMF说明/RP1_CNC_CMF_Specification.xlsx)、[CMF 说明](02_Manufacturing/01_CNC/CMF说明/) |
| 3D 打印 | [加工 BOM](02_Manufacturing/02_3D_Printing/RP1_3D_Print_BOM.xlsx)、[STEP 模型](02_Manufacturing/02_3D_Printing/STEP_3D模型/)、[PDF 图纸](02_Manufacturing/02_3D_Printing/PDF文件/) | [CMF 规格表](02_Manufacturing/02_3D_Printing/CMF说明/RP1_3D_Print_CMF_Specification.xlsx)、[CMF 说明](02_Manufacturing/02_3D_Printing/CMF说明/) |
| 橡胶件 | [加工 BOM](02_Manufacturing/03_Rubber/RP1_Rubber_BOM.xlsx)、[STEP 模型](02_Manufacturing/03_Rubber/STEP_3D模型/)、[PDF 图纸](02_Manufacturing/03_Rubber/PDF文件/) | [CMF 规格表](02_Manufacturing/03_Rubber/CMF说明/RP1_Rubber_CMF_Specification.xlsx)、[CMF 说明](02_Manufacturing/03_Rubber/CMF说明/) |

加工 BOM 按料号汇总单机用量；5DOF、7DOF 分列，均对应运控头配置。

文件名中的料号和修订后缀用于对应图纸与模型。
