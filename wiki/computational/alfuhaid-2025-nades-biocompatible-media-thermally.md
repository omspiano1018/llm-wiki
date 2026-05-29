---
title: "NADES as Biocompatible Media for Thermally Stable RNA Molecules"
authors: Lamya Al Fuhaid, Shahryar Khattak, Arwa Alghuneim, Imed Gallouzi, Young Hae Choi, Robert Verpoorte, Geert-Jan Witkamp, Andreia Farinha
year: 2025
doi: 10.1101/2025.07.23.665770
source: alfuhaid-2025-nades-biocompatible-media-thermally.md
category: computational
pdf_path: C:/Users/User/Desktop/llm-wiki/papers/NADES as Biocompatible Media for Thermally Stable RNA Molecules.pdf
pdf_filename: NADES as Biocompatible Media for Thermally Stable RNA Molecules.pdf
source_collection: external
tags: [rna-storage, nades, deep-eutectic-solvents, mrna-stability, cold-chain-free, choline-chloride, biocompatibility]
---

## Summary
Al Fuhaid et al. (2025) demonstrate that Natural Deep Eutectic Solvents (NADES) — specifically choline chloride-based formulations — can preserve mRNA integrity and in cellulo translatability for at least four months at room temperature (21°C) and 48 hours at 50°C, relative to a −80°C standard. NADES concentrations also maintained >99% HeLa cell viability, establishing both their efficacy as RNA storage media and their biocompatibility. This preprint proposes NADES as a practical, cold-chain-free alternative for RNA-based biomedical applications including vaccines.

## Key Contributions
- **Proof-of-concept for NADES as RNA storage medium**: first evaluation of translatability (not just physical integrity) of mRNA stored in NADES.
- **Choline chloride vs. betaine**: betaine-based NADES (1–5) failed; choline chloride-based NADES (A, C, D, E) succeeded. NADES C was selected as best performer.
- **Temperature robustness**: at 50°C, NADES-stored mRNA retained ~70% (24 h) and ~50% (48 h) translatability vs. ~50% and ~15% in water.
- **Temperature-fluctuation resistance**: repeated 50°C ↔ 4°C cycling did not impair NADES-stored mRNA — relevant to real-world transport scenarios.
- **Biocompatibility**: >98% cell viability confirmed in HeLa cells at working concentrations.

## Methodology and Architecture
**NADES formulation screen**: Ten NADES prepared — betaine-based (1–5) and choline chloride-based (A–E) — combined with glycerol and/or disaccharides. Only crystallization-stable formulations advanced to biological testing.

**RNA model**: in vitro-transcribed mCherry mRNA with pseudouridine and 5-methylcytidine modifications. Stored in NADES or water at 4°C, 21°C, 37°C, 50°C, and temperature-fluctuation profiles.

**Translatability assay**: HeLa cells transfected with stored mRNA; % mCherry-expressing cells measured by flow cytometry (Texas Red filter), normalized to −80°C control.

**Biocompatibility assay**: HeLa cells treated with NADES (2–20 µg/mL); viability by fluorescence microscopy and flow cytometry at 24 h.

## Results
| Condition | Water | NADES C |
|---|---|---|
| 24 h, 37°C | ~90% | ~90% |
| 48 h, 37°C | ~85% | ~85% |
| 24 h, 50°C | ~50% | ~70% |
| 48 h, 50°C | ~15% | ~50% |
| ≥4 months, 21°C | — | >50% |

Temperature cycling (50°C ↔ 4°C × 4 shifts): water-stored mRNA degraded progressively; NADES C-stored mRNA remained stable.

Cell viability after NADES treatment: >98% in all tested formulations.

## Related Papers
- [[computational/kim-2022-a-deep-eutectic-based]] — deep eutectic solvents for RNA/nucleic acid preservation; NADES are a natural-metabolite subset of DES
- [[computational/pedro-2018-cholinium-based-goods-buffers]] — cholinium (choline-based) buffers for biological applications; mechanistic context for choline chloride NADES
- [[computational/verissimo-2026-ionic-liquids-deep-eutectic]] — ionic liquids and DES for nucleic acid biopharmaceutical stabilization; direct comparison class
- [[computational/yu-2026-ionic-liquids-as-alternative]] — ionic liquids as alternative RNA storage media
- [[computational/khan-2025-freeze-drying-mrna-lnps-vaccines]] — lyophilization as competing cold-chain-free approach for mRNA-LNP vaccines
- [[computational/zhen-2026-drying-technologies-messenger-rna]] — drying technologies for mRNA-LNP; complementary cold-chain-free strategy
- [[computational/lou-2014-review-room-temperature-storage]] — room-temperature biospecimen storage review; broader context
- [[computational/fabre-2014-efficient-method-room-temperature]] — efficient room-temperature RNA storage method
- [[transcriptomics/kornienko-2024-rna-stability-review-structural]] — structural determinants of RNA stability; mechanistic background
