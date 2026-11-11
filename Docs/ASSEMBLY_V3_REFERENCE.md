# Mag-Cup 4D — v3 assembly and printing reference

**IMPORTANT:** This document is transcribed and condensed from the repository's **v3 Chinese engineering archive**. It is **not a verified guide for the uploaded v4 STL/PDF**. Read the [version status](RELEASE_CHECKLIST.md) before attempting a v4 build.

## v3 part reference

- Ferromagnetic galvanized steel square tube: 40 × 40 × 4 mm section, cut to 30 mm length; **measured 32.0 mm internal opening** in the prototype.
- Four N52 NdFeB blocks: 30 × 10 × 10 mm, magnetized **through the 10 mm thickness**.
- PETG inner liner: legacy file name `liner_v3.stl` (not included in this repository).
- PETG outer cup/base: legacy file name `cup_v3.stl` (not included in this repository).
- Standard 1.5 mL / 2 mL microcentrifuge tube, subject to actual fit check.

The above is a **v3-only BOM**. See [BOM_v3_reference.csv](../BOM/BOM_v3_reference.csv). No quantity or fit for v4 is implied.

## Printing parameters reported for v3

| Setting | Archived value |
| --- | --- |
| Material | PETG |
| Layer height | 0.2 mm |
| Perimeters | 3 |
| Liner infill | at least 40% |
| Cup infill | at least 30% |
| Supports | none |
| Orientation | liner flange upwards; cup opening upwards |

The v3 liner contains thin **0.5 mm** material near magnet-slot bottoms. Inspect for holes, gaps, or mechanical weakness before use. These parameters have **not** been verified with the v4 STL.

## Assembly sequence reported for v3

1. Check that the actual steel tube's internal dimensions and corner radii fit the printed liner; remove sharp burrs safely.
2. Seat the v3 liner inside the steel tube, with the flange resting on the upper edge.
3. Before installation, determine and label the **relative polarities** of all four magnets using a properly identified reference magnet or polarity tester. Arrange the four **inward-facing** pole faces to alternate N/S/N/S around the tube.
4. Insert magnets individually **from below** into the v3 liner slots, using non-ferromagnetic tools while keeping fingers out of potential pinch points.
5. Insert the tube-and-liner assembly into the printed cup/base. Inspect for stability, magnet retention, and unobstructed tube fit.

**Stop if parts bind or crack.** Incorrect magnet orientation, mismatched clearances, or damaged 3D-printed barriers can compromise function or safety. This sequence is a historical description, **not a certified assembly procedure**.

## Use and validation boundary

The archive describes keeping the sample tube in the magnet rack during supernatant removal and approaching between bead-accumulation regions. Separation timing and performance depend on the **specific magnetic beads, labelling chemistry, and assay**; use a validated kit protocol and establish appropriate controls. The archive records a qualitative internal result, not a reproducible performance dataset.

## 中文提示

以上尺寸、打印参数、安装顺序均来自 **V3 历史存档**。仓库当前上传的是 V4 的 STL 与 PDF；完成 V4 对照前，**不要依据本文件采购或直接装配 V4**。必须核实磁铁充磁方向、四极交替顺序、钢管实际内腔和打印件配合间隙。

Source: [自制四极磁力架_设计存档.md](../%E8%87%AA%E5%88%B6%E5%9B%9B%E6%9E%81%E7%A3%81%E5%8A%9B%E6%9E%B6_%E8%AE%BE%E8%AE%A1%E5%AD%98%E6%A1%A3.md)
