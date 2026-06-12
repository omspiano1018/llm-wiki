---
title: "Novel Biocompatible and Self-buffering Ionic Liquids for Biopharmaceutical Applications"
authors: Mohamed Taha, Mafalda R. Almeida, Francisca A. e Silva, Pedro Domingues, Sónia P. M. Ventura, João A. P. Coutinho, Mara G. Freire
year: 2015
doi: 10.1002/chem.201405693
source: taha-2015-novel-biocompatible-and-self-buffering-ionic.md
category: computational
pdf_path: C:/Users/User/Desktop/llm-wiki/papers/Novel biocompatible and self-buffering ionic liquids for biopharmaceutical applications.pdf
pdf_filename: Novel biocompatible and self-buffering ionic liquids for biopharmaceutical applications.pdf
source_collection: external
tags: [ionic-liquid, Good's-buffers, cholinium, self-buffering, aqueous-biphasic-system, ABS, IgY, protein-purification, biocompatibility, COSMO-RS]
---

## Summary
Taha et al. (2015) introduce **cholinium-based Good's buffer ionic liquids (GB-ILs)** — the founding work for the self-buffering GB-IL platform later used by the same Aveiro group for RNA stabilization. Pairing the biocompatible cholinium cation with Good's buffer anions (MES, Tricine, TES, HEPES, CHES) yields ILs that **buffer themselves within the physiological pH 6–8 range** and show low ecotoxicity. Combined with the biodegradable polymer **PPG 400**, four of these GB-ILs form **aqueous biphasic systems (ABS)** that extract **immunoglobulin Y (IgY)** from chicken egg yolk in a single step at **79–94% efficiency**. Computational analysis attributes the preferential partitioning of IgY into the IL-rich phase to **hydrogen-bonding and van der Waals interactions**.

## Key Contributions
- First report of **self-buffering cholinium GB-ILs** (the chemical foundation reused in [[computational/pedro-2018-cholinium-based-goods-buffers]] for RNA).
- Intrinsic buffering near physiological pH eliminates a separate phosphate buffer (which would chelate protein-essential metal ions).
- Low ecotoxicity for most GB-ILs; biodegradable, nutrient-derived cholinium cation.
- New **biocompatible polymer–IL ABS** (GB-IL + PPG 400) — avoids the high ionic strength of salt-based ABS.
- **Single-step IgY extraction** at 79–94% efficiency without harsh solvents.
- Mechanistic insight from molecular modeling (H-bonding + van der Waals dominate partitioning).

## Methodology and Architecture
**IL panel** — cholinium cation neutralized with five Good's buffer anions:
- [Ch][MES], [Ch][Tricine], [Ch][CHES], [Ch][HEPES], [Ch][TES]

**Characterization workflow**:
- Protonation constants (pKa1/pKa2) by potentiometric titration (HYPERQUAD 2008) → confirms self-buffering in pH 6–8.
- Ecotoxicity by Microtox assay (*Vibrio fischeri*, 30 min) → EC₅₀.
- Ternary phase diagrams (GB-IL + PPG 400 + water, 25 °C); binodal curves empirically fitted.
- IgY extraction from chicken egg yolk; partition quantified.
- COSMO-RS / molecular interaction analysis to identify dominant forces.

**Key design choice**: replacing imidazolium ILs (which shift pH and denature proteins) and salt-based ABS (high ionic strength) with a self-buffering, biocompatible cholinium GB-IL + biodegradable polymer system suited to fragile high-value antibodies.

## Results
| Property | Finding |
|----------|---------|
| Self-buffering range | pH ~6–8 (cholinium slightly lowers GB pKa2 vs free buffer) |
| Ecotoxicity (EC₅₀, higher = safer) | [Ch][HEPES] ≈19584, [Ch][MES] ≈9789, [Ch][Tricine] ≈4588 g·dm⁻³; [Ch][TES] non-toxic; [Ch][CHES] ≈209 g·dm⁻³ (most toxic) |
| ABS formation with PPG 400 | Yes for HEPES, Tricine, TES, MES; **No for CHES** (anion too hydrophobic) |
| IgY extraction efficiency | **79–94% single step** (water-soluble protein fraction) |
| Partitioning driver | Hydrogen-bonding + van der Waals interactions |

## Related Papers
- [[computational/pedro-2018-cholinium-based-goods-buffers]] — same group extends these cholinium GB-ILs from protein (IgY) extraction to recombinant small-RNA stabilization (+14 °C Tm, 30-day RT stability)
- [[computational/verissimo-2026-ionic-liquids-deep-eutectic]] — broader perspective situating cholinium/biocompatible ILs among nucleic-acid biopharmaceutical stabilization platforms
- [[computational/yu-2026-ionic-liquids-as-alternative]] — choline–amino-acid ILs applied to LNP-mediated mRNA delivery
