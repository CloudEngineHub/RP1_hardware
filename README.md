# RP1 Hardware

English | [简体中文](README_CN.md)

Hardware design and manufacturing files for the RoboParty RP1 humanoid robot: mechanical parts, PCB production data, wiring harnesses and bills of materials.

![RP1 front, side and rear views](assets/images/robot-overview.png)

## Documentation

[Hardware architecture (PDF)](00_Docs/RP1_Hardware_Architecture.pdf)

| Resource | Contents |
| --- | --- |
| [Mechanical files](01_Mechanic/README.md) | Assemblies, part models, drawings, CNC, 3D printing and rubber parts |
| [PCB files](02_PCB/README.md) | Board BOMs, Gerbers, placement data, 3D models and fabrication requirements |
| [Wiring harnesses](03_Harness/README.md) | Harness BOM, drawings and assembly requirements |
| [Robot BOMs](04_BOM/README.md) | Part numbers and quantities for each configuration |

### Robot configurations

| Configuration | BOM |
| --- | --- |
| 5DOF + MotionHead | [RP1_BOM_5DOF_MotionHead.xlsx](04_BOM/RP1_BOM_5DOF_MotionHead.xlsx) |
| 7DOF + MotionHead | [RP1_BOM_7DOF_MotionHead.xlsx](04_BOM/RP1_BOM_7DOF_MotionHead.xlsx) |

## CAD Downloads

CAD files are available in [Releases](https://github.com/Roboparty/rp1_hardware/releases/tag/v0.1.0). Manufacturing files, PCB data, harness drawings and BOMs are included in this repository.

| Download | Contents |
| --- | --- |
| [RP1_SolidWorks_Source.zip](https://github.com/Roboparty/rp1_hardware/releases/download/v0.1.0/RP1_SolidWorks_Source.zip) | SolidWorks assemblies, parts and referenced models |
| [RP1_Neutral_Models.zip](https://github.com/Roboparty/rp1_hardware/releases/download/v0.1.0/RP1_Neutral_Models.zip) | STEP and X_T models |
| [RP1_Drawings.zip](https://github.com/Roboparty/rp1_hardware/releases/download/v0.1.0/RP1_Drawings.zip) | SolidWorks drawings and PDFs |

Download and extract the CAD packages you need, keeping the directory structure inside each archive. To edit native SolidWorks drawings, also download the corresponding SolidWorks source package.

The main assembly is `01_Mechanic/01_Source_CAD/01_Assemblies/RP1.3.4整机.SLDASM`. A STEP model is provided at the same location. See [mechanical files](01_Mechanic/README.md) for details.

## Drawing Previews

### CNC part drawing · YCL.M000642

[![YCL.M000642 upper-arm body machining drawing](assets/images/cnc-part-drawing.png)](<01_Mechanic/02_Manufacturing/01_CNC/Common/YCL.M000642 大臂上本体（01版）.PDF>)

[Open the CNC drawing (PDF)](<01_Mechanic/02_Manufacturing/01_CNC/Common/YCL.M000642 大臂上本体（01版）.PDF>)

### BACKHUB PCB layout

[![BACKHUB V2.1 component placement drawing](assets/images/pcb-layout.png)](02_PCB/12_RBE_PWR_BACKHUB/06_PCB_PDF_BACKHUB_V2.1.pdf)

[Open the board drawing (PDF)](02_PCB/12_RBE_PWR_BACKHUB/06_PCB_PDF_BACKHUB_V2.1.pdf)

### BODY01 wiring harness

[![BODY01 wiring harness drawing](assets/images/harness-drawing.png)](03_Harness/Drawings/RP1-BODY01-0线材.pdf)

[Open the harness drawing (PDF)](03_Harness/Drawings/RP1-BODY01-0线材.pdf)

## Contributing

Found a file error or have a design improvement? Open an [issue](https://github.com/Roboparty/rp1_hardware/issues) with the part number or board revision and the relevant file path.

## License

RoboParty-owned hardware designs are licensed under [CERN-OHL-W-2.0](LICENSE). Documentation is licensed under [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/). Third-party files retain their original terms. See [LICENSES.md](LICENSES.md) for the scope of each licence.
