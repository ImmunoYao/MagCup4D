# Mag-Cup 4D — checklist before a reproducible v4 release

Status checked: **2026-11-11**. This is a documentation and repository audit, **not a CAD, magnetic-field, or experimental validation**.

## Verified to be in the repository

- [x] Public GitHub repository and README.
- [x] `cup_v4.stl`.
- [x] `cup_v4_drawing.pdf`.
- [x] Chinese `自制四极磁力架_设计存档.md` (document explicitly identifies **v3**).
- [x] Complete `LICENSE` text for CERN-OHL-W-2.0.
- [x] Archived **v3** BOM and reference assembly notes, clearly marked as legacy.

## Still required / 未完成

- [ ] **Version cross-check:** identify what `cup_v4.stl` models and whether it contains one or multiple parts; compare dimensions against `cup_v4_drawing.pdf` and v3 document.
- [ ] **Editable CAD:** upload the native CAD project and ideally neutral STEP exports for each custom designed component.
- [ ] **Complete v4 printing set:** confirm all required v4 printed parts are present, including any revised inner liner; do not rename v3 files as v4.
- [ ] **v4 BOM:** confirm steel yoke dimensions, magnetic material/grade, block dimensions and magnetization axis, printed part quantities, and tolerance/fit.
- [ ] **v4 instructions:** document magnet polarity diagram, assembly order, printing orientation, parameter ranges, and any support requirements.
- [ ] **Visuals:** add at least one finished-build photograph and an annotated exploded assembly view, both cleared for public release.
- [ ] **Reproducibility:** report at least one complete build and any test method/results with the version identified; clearly separate internal test observations from independently verified performance.
- [ ] **Rights review:** confirm that all contributed CAD/drawing content can legally be redistributed under the stated licence and that any employer/institutional or third-party rights are handled.
- [ ] **First Release:** only after the version-matched build package is ready, publish a GitHub Release (for example, `v1.0.0` if production-ready, or a `v0.x` prototype release with limitations documented).

## Publication rule

**Do not claim “complete v4 open-source manufacturing files” until native or editable design files and every required version-matched manufactured part are included.** The repository may remain publicly accessible as a work-in-progress meanwhile.

## 中文说明

当前 V4 STL/PDF 与 V3 设计存档的对应关系未完成审查。最重要的四项缺口：**V4 CAD 原文件、V4 全套零件、V4 材料清单、V4 组装及磁极示意图**。在补齐之前，不要发布“已完全可复现”的正式版本。
