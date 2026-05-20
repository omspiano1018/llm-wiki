---
title: "A biocompatible and recyclable ionic liquid platform for long-term and high temperature plant RNA stabilization"
authors: Shashini De Silva, Cecilia Cagliero, Morgan R. Gostel, Gabriel Johnson, Jared L. Anderson
year: 2026
doi: 10.1016/j.aca.2026.345501
category: computational
pdf_path: C:/Users/User/Desktop/llm-wiki/papers/de-silva-2026-a-biocompatible-and-recyclable.pdf
pdf_filename: de-silva-2026-a-biocompatible-and-recyclable.pdf
source_collection: external
---

## One-line Summary
20% (w/v) choline glutamate ionic liquid protects complex plant RNA from thermal and enzymatic degradation, is recyclable for ≥5 cycles, and requires no freezing.

## 1. Document Information
- **Journal**: Analytica Chimica Acta 1407 (2026) 345501
- **Institution**: Iowa State University (Anderson lab); Università di Torino; Morris Arboretum / Univ. Pennsylvania; Smithsonian Institution
- **Received**: 2026-02-01; Accepted: 2026-04-06

## 2. Key Contributions
- First IL-based platform designed specifically for heterogeneous total **plant RNA** (not purified/commercial RNA)
- Identified **20% (w/v) choline glutamate** as optimal stabilization medium from a panel of choline-based ILs
- RNA integrity retained even at **80–90°C** (controls degraded at 70°C)
- **Long-term stability**: ≥72 h at 40°C; delayed degradation by several weeks at room temperature
- IL recycled and reused for **≥5 cycles** without loss of RNA purity or integrity
- Multi-metric validation framework: NanoDrop (A260/280, A260/230), Qubit fluorometer, Bioanalyzer microfluidic electrophoresis

## 3. Methodology and Architecture

### RNA source
Total plant RNA extracted from plant tissue (heterogeneous: mRNA, rRNA, tRNA; 25S and 18S rRNA used as integrity markers).

### IL synthesis
Choline-based ILs synthesized by neutralization of choline hydroxide (45 wt% aq. solution) with organic acids (e.g., L-glutamic acid). pH adjusted; solvent removed.

### Stability assays
- **Short-term thermal**: incubate RNA in IL at 40–90°C; assess with Bioanalyzer
- **Long-term ambient/40°C**: multi-week time-course
- **RNase challenge**: IL environment inactivates nucleases (choline cation effect)

### Analytical framework
| Method | Metric | What it measures |
|--------|--------|-----------------|
| NanoDrop | A260/280, A260/230 | Purity, contaminants |
| Qubit | RNA concentration | Selective fluorescence quantification |
| Bioanalyzer | RIN / 28S:18S ratio | RNA structural integrity |
| Agarose gel | Band pattern | Qualitative integrity |

### Recyclability
RNA extracted from IL → IL recovered by precipitation/filtration → reused for next RNA stabilization cycle.

## 4. Key Results and Benchmarks
- **Temperature stability**: choline glutamate suppressed degradation at 80–90°C; control RNA degraded at 70°C
- **40°C storage**: ≥72 h with intact RNA (controls degraded faster)
- **Room temperature**: delayed degradation by several weeks vs. nuclease-free water control
- **Recyclability**: 5 cycles tested; no detectable loss of RNA purity or integrity
- **Purity metrics**: A260/280 and A260/230 comparable to controls after IL treatment and RNA recovery

## 5. Limitations and Future Work
- Limited to choline-based ILs; other IL families not tested for plant RNA
- Long-term stability beyond several weeks not characterized
- Scale-up to field conditions (actual field sampling in tropics etc.) not demonstrated
- RNA recovery efficiency across cycles not quantified in detail
- Comparison with commercial products (GenTegra, RNAstable) not performed head-to-head

## 6. Related Work
- Choline dihydrogen phosphate extends siRNA shelf-life up to 3 months (cited as [19])
- Cholinium Good's buffer ILs for small RNA stabilization (Pedro et al. 2018 — [[computational/pedro-2018-cholinium-based-goods-buffers]])
- Amino acid IL platforms for sRNA extraction from bacterial lysates (cited as [22])
- Commercial products: GenTegra RNA, RNAstable, RNAshell (dry-state storage, not IL-based)

## 7. Glossary
- **IL (Ionic Liquid)**: organic molten salt with melting point ≤100°C; negligible vapor pressure; structurally tunable
- **Choline glutamate**: IL formed from choline cation + glutamate anion; biocompatible amino acid-based IL
- **RIN (RNA Integrity Number)**: 1–10 scale from Bioanalyzer; 10 = fully intact
- **28S:18S ratio**: ratio of ribosomal RNA bands; ~2.0 for intact mammalian RNA
- **A260/280**: purity ratio; ~2.0 for pure RNA (protein contamination lowers ratio)
- **A260/230**: secondary purity ratio; ~2.0–2.2 for pure RNA (solvent contamination lowers ratio)
- **RNase**: ribonuclease enzyme; major cause of RNA degradation in biological samples
