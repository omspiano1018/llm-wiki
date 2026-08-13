---
title: "Biological Stability and Activity of siRNA in Ionic Liquids"
authors: Rowshon R. Mazid, Umaporn Divisekera, Wenrong Yang, Ranganathan Vijayaraghavan, Douglas R. MacFarlane, Christina Cortez-Jugo, Wenlong Cheng
year: 2014
doi: 10.1039/C4CC05086J
source: mazid-2014-biological-stability-and-activity-of.md
category: computational
pdf_path: C:/Users/User/Desktop/llm-wiki/papers/mazid-2014-biological-stability-and-activity-of.pdf
pdf_filename: mazid-2014-biological-stability-and-activity-of.pdf
source_collection: external
tags: [ionic-liquid, CDP, choline-dihydrogen-phosphate, siRNA, RNase-protection, RNA-storage, gene-knockdown, biocompatible, cold-chain-free]
---

## Summary
Mazid et al. (Cheng & MacFarlane groups, Monash University) give the **first report of siRNA stability in an ionic liquid**. Storing siRNA in **hydrated choline dihydrogen phosphate (CDP) IL** (20% or 50% w/w in water, buffered ~pH 7) dramatically slows RNase A degradation: naked siRNA is fully degraded in **PBS within 0.5 h**, whereas in CDP IL it survives for **up to three months**. Crucially, the recovered siRNA is **still active** — eGFP siRNA drives clear gene knockdown in eGFP-HeLa cells even after RNase A challenge, whereas PBS-stored siRNA loses all knockdown activity.

This is a **founding aqueous-IL paper** for the wiki's RNA-in-ionic-liquid thread: it establishes CDP (the choline/phosphate IL that later Good's-buffer and cholinium work builds on) as a **room-temperature, refrigeration-free storage medium** for nucleic acids, with protection driven by high ionic strength rather than water removal.

## Key Contributions
- **First-ever demonstration** that an ionic liquid stabilizes siRNA (no prior siRNA-in-IL report existed).
- **CDP IL extends siRNA shelf life from minutes/hours to months** against RNase A — up to ~4 months at low nuclease load in 50% IL.
- **Function is retained**: 69–74% eGFP knockdown from IL-stored siRNA after RNase A, vs 0% for PBS-stored siRNA.
- Simultaneous enhancement of **structural (CD), thermal (Tm +4 to +9 °C), and biological** stability, with more negative duplex ΔG°₂₅.
- **Low cytotoxicity** at working concentrations (alamarBlue), so the IL need not be removed before biological use.
- Positions ILs as **next-generation biobuffers** that could replace lyophilization/cold-chain for siRNA storage and transport.

## Methodology and Architecture
- **IL**: choline dihydrogen phosphate (CDP), hydrated, at **20%** and **50% (w/w)** in water; buffered near the H₂PO₄⁻/HPO₄²⁻ region (~pH 7). Control = 0.01 M PBS.
- **siRNAs**: CD45 siRNA and eGFP siRNA (dsRNA, ~21mer).
- **Nuclease challenge**: RNase A, **0.25–2 mg/mL**; incubated at 37 °C then held at ambient temperature for time-lapse degradation.
- **Assays**: native + denaturing (urea) PAGE (resolving ds- vs ss-siRNA bands against a 21mer marker); circular dichroism (A-type dsRNA signature); UV thermal melting with van't Hoff two-state analysis (ΔH°, TΔS°, ΔG°₂₅, Tm); flow cytometry of eGFP-HeLa fluorescence for knockdown (Lipofectamine RNAiMAX transfection); alamarBlue viability.
- **Proposed protection mechanism**: siRNA degradation proceeds in two steps — (1) RNase A destabilizes/de-winds the duplex by binding single strands, (2) RNase A cleaves the P–O bond. **High ionic strength in CDP IL retards step 1**, so ds- and ss-siRNA co-exist (the observed double bands) and overall degradation is slowed.

## Results
| Metric | PBS | 20% (w/w) CDP IL | 50% (w/w) CDP IL |
|---|---|---|---|
| siRNA after RNase A | fully degraded in **0.5 h** | clear bands at 4 h | clear bands at 4 h |
| Full degradation @ 2 mg/mL RNase A | — | ~14 days | ~24 days |
| Full degradation @ 1 mg/mL RNase A | — | ~50 days | ~77 days |
| Full degradation @ 0.25 mg/mL RNase A | — | — | ~4 months |
| eGFP siRNA Tm (1 µM) | 61.5 °C | 65.8 °C | 70.2 °C |
| ΔG°₂₅ (kcal/mol) | −16.8 | −23.2 | −30.5 |
| Knockdown, no RNase A | 80% | 74% | 80% |
| Knockdown, with RNase A | **0%** | **69%** | **74%** |

- eGFP siRNA in 50% IL still gave native-gel bands after **three months**.
- CD confirms the A-type dsRNA structure survives RNase A in IL (lost in PBS); slight crossover red shift in IL, larger at 50%.
- Cytotoxicity negligible and equal for 20% vs 50% IL → knockdown is siRNA-specific, not cell death.

**Mechanism of protection = ionic-strength-slowed de-winding.** Unlike dry-state or phase-exclusion approaches, CDP IL keeps siRNA in an *aqueous* medium but the high ionic strength slows RNase A's ability to unwind the duplex, buying months of stability while keeping the siRNA functional.

## Significance & Caveats
- **Founding aqueous-IL nucleic-acid storage result**: shows a biocompatible choline/phosphate IL can replace cold-chain storage for a functional therapeutic RNA — the conceptual seed for later cholinium and Good's-buffer IL RNA work in this wiki.
- **Caveats**: only RNase A tested (serum/other RNases flagged as future work); single IL at two concentrations; mechanism inferred from gel/CD rather than directly resolved; activity shown only in cultured HeLa cells via lipofection, no in vivo delivery.

## Related Papers
- [[overviews/ionic-liquid-rna-storage-state-and-hydrolysis]] — physical state of RNA and how degradation is suppressed in IL media; this is an early aqueous-IL, ionic-strength-based example
- [[computational/pedro-2018-cholinium-based-goods-buffers]] — cholinium Good's-buffer ILs raising RNA Tm; same choline-IL family extended to storage-stability
- [[computational/de-silva-2026-a-biocompatible-and-recyclable]] — aqueous choline-glutamate IL stabilizing plant RNA at high temperature
- [[computational/dinh-2025-room-temperature-preservation-of-mrna]] — hydrophobic DES protecting mRNA by phase exclusion of RNase (contrast: non-aqueous vs this aqueous-IL, ionic-strength mechanism)
- [[computational/verissimo-2026-ionic-liquids-deep-eutectic]] — critical perspective on ILs/DESs for siRNA/mRNA/ASO biopharmaceuticals
- [[computational/egorova-2021-ionic-liquids-prospects-for-nucleic]] — foundational review of ILs for nucleic-acid handling and delivery
- [[computational/mirhadi-2024-utilizing-ionic-liquids-as-eco]] — ILs as biocompatible carriers/stabilizers for nucleic acids incl. siRNA
- [[computational/alfuhaid-2025-nades-biocompatible-media-thermally]] — choline-chloride NADES room-temperature mRNA storage (related cold-chain-free concept)
