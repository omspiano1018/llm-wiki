---
title: "Room-Temperature Preservation of mRNA using Deep Eutectic Solvent"
authors: Hoang T. Dinh, Michael Kegel, Drew Weissman, Jilian R. Melamed, Kathleen J. Stebe, Daeyeon Lee
year: 2025
doi: 10.26434/chemrxiv-2025-js4lr-v2
source: dinh-2025-room-temperature-preservation-of-mrna.md
category: computational
pdf_path: C:/Users/User/Desktop/llm-wiki/papers/dinh-2025-room-temperature-preservation-of-mrna.pdf
pdf_filename: dinh-2025-room-temperature-preservation-of-mrna.pdf
source_collection: external
tags: [deep-eutectic-solvent, hDES, mRNA, RNA-storage, RNase-protection, non-aqueous, cold-chain-free, hydrophobic, extraction]
---

## Summary
Dinh et al. (Weissman/Lee labs, UPenn) introduce a **metal-free hydrophobic deep eutectic solvent (hDES)** — 1-decanol + methyltrioctylammonium chloride (MTAC) — that extracts full-length mRNA at **~100% efficiency**, **shields it from RNase A**, and **preserves it intact at room temperature for at least 227 days (~7.5 months)**. Unlike prior IL/DES RNA-extraction systems, it uses no toxic heavy metals and works on **clinically relevant mRNAs** (2.0-kb FLuc2, 4.2-kb SARS-CoV-2 spike, with N1-methylpseudouridine / CleanCap / poly(A)), with recovered mRNA retaining translatability in HEK293 cells.

This is the **non-aqueous counterpart** to the aqueous choline-IL RNA-storage work in this wiki: instead of *managing* water in a high-ion aqueous solution, the hDES protects mRNA by **partitioning it into a water-immiscible phase that physically excludes both free water and RNase**.

## Key Contributions
- First use of a **hydrophobic DES to preserve full-length mRNA** at room temperature (prior work used short/yeast model RNA without integrity validation).
- **Metal-free** formulation (1-decanol:MTAC, optimal molar ratio β = 2), avoiding the NiCl₂/heavy-metal magnetic DES & IL systems whose metal ions actually cleave RNA.
- **~100% extraction efficiency** across 1.6–4.2 kb mRNAs with clinical caps/modifications.
- **RNase shielding by exclusion**: at pH 7 (below RNase A pI 9.6) the enzyme cannot enter the hDES, so mRNA stays intact 1 h at 37 °C while the aqueous control is fully degraded.
- **227-day** room-temperature shelf life vs. complete degradation of the aqueous (0.1 M Tris pH 7) control.
- **Chaotrope-assisted recovery**: NaClO₄ raises back-extraction to ~70% (vs ~17% with NaCl; 1–22% for prior heavy-metal ILs).

## Methodology and Architecture
- **Solvent**: 1-decanol (HBD) : MTAC (HBA, "N8881⁺"), β = n(decanol):n(MTAC) = 2 → self-assembled amphiphilic nanostructure with polar/nonpolar domains. β = 4 → aggregation; β ≥ 20 → no extraction.
- **Extraction physics**: mRNA complexes with cationic MTAC; partitioning depends on mRNA charge/conformation, tuned by **pH and ionic strength** → four regimes (turbid precipitation / extraction ~100% / mRNA–MTAC membrane / no extraction). The extraction window overlaps standard biomanufacturing buffers (Tris 50–100 mM neutral pH; acetate 100 mM pH 5).
- **Recovery**: high-salt buffer screens mRNA–MTAC attraction. 0.37 M NaCl → ~17%; 0.37 M **NaClO₄ (chaotrope)** → ~70%.
- **Integrity / activity**: capillary gel electrophoresis (Bioanalyzer pseudogel + electropherogram) confirms no fragmentation; FLuc2 bioluminescence after HEK293 transfection confirms retained translatability.
- **RNase test**: RNase A partitioning measured pH 4–9 (0% below pH 6.5, ~13% at pH 9); protection holds at pH 7 but fails at pH 9 where the enzyme partitions into and is *more* active in the hDES.
  - **RNase A amounts** — purchased stock **100 mg/mL (7000 units/mL, QIAGEN)**; conversion uses ε = 0.71 mL·mg⁻¹·cm⁻¹. Actual mRNA-challenge concentrations are far lower: **0.005 µg/mL (pH 9)** and **0.01 µg/mL (pH 7)**, 37 °C for 1 h (Fig. 5). RNase-rich hDES prepared at 0.305 µg/mL (~12% partition); pH-6 activity test used 0.01 µg/mL then RNasin (40 U/µL) to inactivate.
- **Long-term storage**: FLuc mRNA in water vs 1-decanol:MTAC, room temperature, dark, assayed day 4 and day 227.

### Analytical Instruments Used
| Instrument | Make/Model | Purpose | Sample amount actually used (paper) |
|---|---|---|---|
| Capillary gel electrophoresis (Bioanalyzer) | Agilent **2100 Bioanalyzer** | mRNA integrity (pseudogel + electropherogram) | Back-extracted aqueous sample; run by Penn Genomics & Sequencing Core — kit not named |
| UV-Vis spectrophotometer | Thermo Scientific **NanoDrop OneC** | RNA concentration via A280 (extraction/recovery efficiency) | 20 µL aliquots; storage samples ~240 µg/mL |
| Microplate reader | model not stated (+ Promega Dual-Glo Luciferase Assay) | FLuc2 bioluminescence = translatability | Cell lysate 23 h post-transfection |
| Viscometer | model not stated | hDES viscosity (447 → 85 cP on water uptake) | Supplementary Fig. 6 |
| Vortexer / centrifuge (sample prep) | — | Phase mixing/separation | Vortex 1500 rpm 60 s; centrifuge 7000 rpm 5 min |

**Note on "minimum requirements":** the paper does **not** specify per-instrument minimum sample volumes / detection limits (these are manufacturer specs, not reported). Only the *actual* volumes/concentrations above are traceable from the text; the Bioanalyzer RNA kit (Nano vs Pico) is not named, so its input range cannot be pinned down from the paper alone.

## Results
| Metric | Result |
|---|---|
| Extraction efficiency | ~100% (1.6–4.2 kb, capped/modified incl. SARS-CoV-2 spike) |
| Back-extraction (NaCl / NaClO₄) | ~17% / ~70% |
| RNase A into hDES | 0% below pH 6.5; ~13% at pH 9 |
| RNase protection (pH 7, 37 °C, 1 h) | hDES intact; aqueous control fully degraded |
| Room-temp shelf life | ≥227 days intact (control degraded) |
| In vitro activity | recovered mRNA ≈ control bioluminescence |

**Mechanism of protection = phase exclusion.** Because most RNases have a high isoelectric point, at acidic/neutral pH they are cationic and cannot complex with the cationic MTAC, so they stay in the aqueous phase and never contact the mRNA. Protection therefore requires pH below the nuclease pI — a key boundary condition.

## Significance & Caveats
- **Beats existing options on shelf life**: commercial liquid formulations (RNAlater, GenTegraRNA) last ~1 week at RT; freeze/spray-dried mRNA ~4 weeks at RT; prior IL/ATPS preserved only short RNAs ~2 weeks. hDES reaches ≥7.5 months.
- **Preprint**, not peer-reviewed. Recovery still ~70% at best; MTAC/1-decanol co-partition into water (downstream purification not fully solved); protection fails at basic pH. Proposed use as a shelf-stable non-aqueous precursor to cationic emulsions/LNPs is not yet demonstrated.

## Related Papers
- [[overviews/ionic-liquid-rna-storage-state-and-hydrolysis]] — physical state of RNA & how hydrolysis is suppressed in IL media; this paper is the non-aqueous, phase-exclusion contrast
- [[computational/alfuhaid-2025-nades-biocompatible-media-thermally]] — NADES (choline chloride) room-temperature mRNA storage; closest precedent in concept
- [[cell-biology/kim-2022-a-deep-eutectic-based]] — earlier deep-eutectic-solvent RNA preservation
- [[computational/de-silva-2026-a-biocompatible-and-recyclable]] — aqueous choline-glutamate IL for total RNA (managing water vs. excluding it)
- [[computational/pedro-2018-cholinium-based-goods-buffers]] — cholinium self-buffering ILs; aqueous-IL stabilization mechanism
- [[computational/verissimo-2026-ionic-liquids-deep-eutectic]] — broader IL/DES stabilization of nucleic-acid biopharmaceuticals
- [[computational/oude-blenke-2022-storage-inuse-stability-mrna]] — cold-chain / storage context for mRNA therapeutics
