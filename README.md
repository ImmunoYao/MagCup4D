# Mag-Cup 4D

**Open-source four-pole magnetic separation rack — prototype hardware**

Mag-Cup 4D (四极磁力架) is a compact magnetic separation rack concept for 1.5 mL and 2 mL microcentrifuge tubes. It uses a four-pole permanent-magnet arrangement with a ferromagnetic yoke. This repository shares the currently uploaded 3D-printing file, drawing, and engineering notes so that other laboratories can inspect and improve the design.

> **Version warning / 版本提示:** The uploaded STL and drawing are named **v4**, but the detailed Chinese engineering archive describes **v3**. A verified v4 bill of materials, editable CAD source, matching list of all required printable parts, and v4-specific assembly instructions are **not yet available** in this repository. Do not assume that v3 dimensions or procedures are identical to v4.
>
> 目前公开的是 V4 STL 和 PDF 图纸，以及 V3 设计存档。**这些文件尚未核对为同一个完整装配版本。** 请勿把 V3 尺寸直接当作 V4 装配尺寸。

## Files / 文件

| File | What it is | Status |
| --- | --- | --- |
| [`cup_v4.stl`](cup_v4.stl) | Uploaded v4 print geometry / V4 打印模型 | Available; companion parts not confirmed |
| [`cup_v4_drawing.pdf`](cup_v4_drawing.pdf) | Uploaded v4 technical drawing / V4 图纸 | Available |
| [`自制四极磁力架_设计存档.md`](%E8%87%AA%E5%88%B6%E5%9B%9B%E6%9E%81%E7%A3%81%E5%8A%9B%E6%9E%B6_%E8%AE%BE%E8%AE%A1%E5%AD%98%E6%A1%A3.md) | Detailed Chinese design archive / 中文设计说明 | **v3 reference only** |
| [`BOM/BOM_v3_reference.csv`](BOM/BOM_v3_reference.csv) | Parts list derived from the v3 archive / V3 材料参考清单 | **Not validated for v4** |
| [`Docs/ASSEMBLY_V3_REFERENCE.md`](Docs/ASSEMBLY_V3_REFERENCE.md) | Legacy assembly and print instructions / V3 组装与打印说明 | **Not validated for v4** |
| [`Docs/RELEASE_CHECKLIST.md`](Docs/RELEASE_CHECKLIST.md) | Outstanding steps before a reproducible v4 release / V4 发布待办 | In progress |
| [`LICENSE`](LICENSE) | CERN-OHL-W-2.0 hardware licence | Included |

## Design context / 设计思路

The **v3 engineering archive** describes four N52 neodymium magnets (30 × 10 × 10 mm, magnetized through the 10 mm thickness) arranged with alternating inward-facing polarities, a ferromagnetic square steel-tube yoke, and PETG-printed structural parts. This description is a **historical reference, not an independently checked v4 parts specification**.

V3 存档采用四块钕铁硼磁铁、导磁钢方管和 PETG 打印结构。装配中最重要的是磁铁面向管孔的极性必须交替排列。请先核对 V4 图纸和实物，不能直接套用 V3 尺寸。

## Build status / 复现状态

- **Available:** One v4 STL, one v4 drawing PDF, and a detailed v3 design record.
- **Missing or unconfirmed:** v4 native/editable CAD; a version-matched list of printable parts; final v4 BOM; complete v4 assembly guide; build photos and reproducible test data.
- **Do not interpret this repository as a fully verified, ready-to-assemble v4 kit yet.**

## Validation / 验证

The v3 engineering archive **reports internal use with a commercial column-free cell-separation kit and acceptable separation purity**. No quantitative dataset, protocol, sample-size details, or independent product-equivalence comparison is supplied here. Therefore these notes should not be read as a verified claim that Mag-Cup 4D matches commercial racks across applications.

V3 设计存档记录了配合商品化分选试剂盒的内部使用结果，但仓库尚未提供完整原始数据或第三方等效性验证。不应将其解释为所有分选场景均达到商品化磁架性能。

## Safety / 安全

Strong neodymium magnets can snap together suddenly, pinch fingers, chip or shatter, and interfere with magnetically sensitive equipment and some implanted medical devices. Use eye protection and appropriate tools; check material and magnet supplier limits before cleaning or heat exposure. Verify retention and stability before using biological samples. **Research use only; not validated for clinical or diagnostic use.**

## Licence / 开源许可

Unless individually noted otherwise, the hardware design files and supporting project documentation in this repository are offered under the **CERN Open Hardware Licence Version 2 – Weakly Reciprocal (CERN-OHL-W-2.0)**. See the complete [LICENSE](LICENSE) text.

The licence permits manufacturing and commercial use subject to its terms; it does **not** imply certification, endorsement, or performance warranty. Rights to third-party product names, trademarks, and separately licensed materials are not granted by this licence.

## Contributions / 参与改进

Please open a GitHub Issue with the file version, printer/material settings, measured dimensions, magnet orientation, and any reproducible test results. Proposed geometry changes should include an editable CAD source as well as an STL export.

欢迎提交复现记录、改进图纸、打印参数和分选测试结果，并注明适用的设计版本。
