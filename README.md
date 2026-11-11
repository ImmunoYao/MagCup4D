# Mag-Cup 4D | 四极磁分选架

**Open-source, four-pole magnetic separation rack for 1.5/2 mL microcentrifuge tubes.**

Mag-Cup 4D 是一套低成本、无柱式磁分选架硬件方案。它使用四块永磁体、导磁钢方管及两件 PETG 3D 打印结构，适用于研究实验室中的磁分选工作流。磁架是硬件，不含磁珠、抗体或分选试剂。

## Two printable parts / 两份打印图纸

| Component | STL | Dimensioned drawing | Purpose |
| --- | --- | --- | --- |
| **Outside（底座外套）** | [Outside STL](MagCup%204D_Outside.stl) | [Outside PDF](MagCup%204D_Outside_drawing.pdf) | Integrated outer cup, base and feet |
| **Inside（内衬）** | [Inside STL](MagCup%204D_Inside.stl) | [Inside PDF](MagCup%204D_Inside_drawing.pdf) | Four magnet slots, central tube guide and upper flange |

These are the two **component names** used throughout the final design. Drawings are in millimetres. The STL files should be printed without scaling.

**安装结构：Inside + 四块磁铁 + 钢方管 + Outside。** Both printed parts are required for one complete rack.

## Bill of materials / 材料清单

| Item | Specification | Quantity installed |
| --- | --- | ---: |
| Ferromagnetic square-tube yoke / 导磁方管 | Galvanized steel 40 × 40 × 4 mm, length 30 mm; prototype measured internal opening 32.0 mm | 1 |
| NdFeB magnets / 钕磁铁 | N52, 30 × 10 × 10 mm, **magnetized through the 10 mm thickness** | 4 |
| Inside print / 内衬 | PETG | 1; an extra spare print is recommended |
| Outside print / 外套 | PETG | 1 |
| Microcentrifuge tube / 离心管 | 1.5 or 2 mL; confirm actual fit | As needed |

See [BOM.csv](BOM.csv).

## Printing / 打印建议

- **Material:** PETG; **layer height:** 0.2 mm; **walls:** 3.
- **Inside:** at least 40% infill; print with flange upward.
- **Outside:** at least 30% infill; print with cup opening upward.
- No support structures in the documented orientation.
- Four open-sided channels on Inside are **intentional**, not STL defects.
- Inspect the thinnest 0.5 mm magnet-slot walls for cracks or holes.

The steel square tube must be **measured** before assembly. Inside/Outside dimensions are based on the prototype geometry and manufacturing tolerances matter.

## Assembly / 装配

1. Check and deburr the 40 × 40 × 4 mm ferromagnetic square tube.
2. Seat **Inside** into the tube; its flange rests on the tube's upper edge.
3. Mark the magnet polarities **before insertion**. The four magnet faces toward the central tube must alternate **N / S / N / S** around the circumference.
4. Push the four magnets **individually from the bottom** using a non-ferromagnetic tool. Keep fingers away from magnetic pinch points.
5. Seat the tube-and-magnet assembly in **Outside**. Confirm tube fit and stability before use.

For further details and operation cautions, see [装配与安全.md](装配与安全.md) and [设计原理与装配说明.md](设计原理与装配说明.md).

## Validation / 验证情况

The design archive records internal use with a commercial column-free cell-separation kit and reports separation purity comparable to the original rack in the tested setup. **Raw performance data and independent equivalence studies have not yet been released**; these observations should not be generalized to every cell type or magnetic bead system.

## Safety / 安全

High-strength neodymium magnets can pinch, crack or shatter; use suitable eye/hand protection and keep them clear of magnetic-sensitive devices and implanted medical devices. Do not autoclave the printed device or the magnets. Research use only; not validated for medical diagnosis.

## Licence / 开源许可

Hardware design files and project documentation are made available under **CERN-OHL-W-2.0**; see [LICENSE](LICENSE) for the complete licence. Commercial manufacture is permitted subject to that licence's terms. **Editable native CAD models are not included in the current file set**. This should be taken into account when assessing completeness against open-hardware documentation standards.

## Contributions / 参与改进

Issues and Pull Requests describing print tolerances, fit measurements, magnetic-field measurements, and experimental reproducibility are welcome. Please label geometry feedback as **Inside** or **Outside**.
