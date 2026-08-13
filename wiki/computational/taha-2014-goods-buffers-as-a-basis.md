---
title: "Good's buffers as a basis for developing self-buffering and biocompatible ionic liquids for biological research"
authors: Mohamed Taha, Francisca A. e Silva, Maria V. Quental, Sónia P. M. Ventura, Mara G. Freire, João A. P. Coutinho
year: 2014
doi: 10.1039/c4gc00328d
source: taha-2014-goods-buffers-as-a-basis.md
category: computational
pdf_path: C:/Users/User/Desktop/llm-wiki/papers/taha-2014-goods-buffers-as-a-basis.pdf
pdf_filename: taha-2014-goods-buffers-as-a-basis.pdf
source_collection: external
tags: [ionic-liquid, Good's-buffers, GB-IL, self-buffering, protein-stabilization, BSA, aqueous-biphasic-system, ABS, molecular-docking, Microtox, biocompatibility]
---

## Summary
Taha et al. (2014, *Green Chem.*) is the **founding paper for Good's buffer ionic liquids (GB-ILs)** from the Aveiro (Freire/Coutinho) group. By neutralizing five Good's buffers (Tricine, TES, CHES, HEPES, MES) with four organic cations — imidazolium [Emim] and tetraalkylammonium [N1111]/[N2222]/[N4444] — they make a **20-member library of self-buffering ILs** whose anions are derived from biological buffers. The GB-ILs buffer in water just like the parent Good's buffers (and usually with higher capacity), can be blended into **universal buffers** spanning pH ~5.2–10.4, **stabilize BSA's α-helical structure better than conventional bromide ILs**, are **non-toxic to *Vibrio fischeri***, and form **aqueous biphasic systems (ABS)** that extract BSA with **100% single-step efficiency**. This work sets the template that the same group later refines with the more biocompatible cholinium cation ([[computational/taha-2015-novel-biocompatible-and-self-buffering-ionic]]) and extends to RNA ([[computational/pedro-2018-cholinium-based-goods-buffers]]).

## Key Contributions
- **First GB-IL concept**: use Good's buffers as IL **anions** so the IL buffers itself near physiological pH — no separate (metal-chelating) buffer needed for protein work.
- **20-member library** from 5 GB anions × 4 cations via simple green aqueous neutralization.
- **Self-buffering verified**: GB-IL mid-point pH and buffering ranges ≈ parent buffers; buffer capacity generally higher. Universal buffer (MES+HEPES+CHES, or their [N1111] ILs) near-linear over **pH 5.2–10.4**.
- **Protein stabilization**: GB-ILs raise BSA α-helix content above conventional ILs; docking + QSAR(log K(HSA)) show stabilization comes from **direct ion–protein binding**, not Hofmeister water-structure effects.
- **Low ecotoxicity** (Microtox), with clear cation/chain-length/anion structure–toxicity trends.
- **ABS extraction**: [N4444][GB] + salt extracts BSA at **100%** in one step.

## Methodology and Architecture
**IL panel** — 5 Good's buffer anions × 4 cations:
- Anions: [Tricine], [TES], [CHES], [HEPES], [MES]
- Cations: [Emim] (1-ethyl-3-methylimidazolium), [N1111], [N2222], [N4444] (tetramethyl-/tetraethyl-/tetrabutylammonium)

**Workflow**:
- Neutralization (hydroxide + excess Good's buffer) → wash → vacuum dry; NMR + DSC characterization, Karl–Fischer water <0.05 wt%.
- Potentiometric titration → pH profiles / buffer capacity.
- DLS (R_H vs T, 25–75 °C) → BSA denaturation temperature T_d; IR amide I/II + curve fitting → secondary structure.
- AutoDock Vina docking (BSA PDB 3v03, DFT-derived charges) + COSMO-RS QSAR log K(HSA) → binding sites/affinities.
- Microtox (*Vibrio fischeri*, 30 min) → EC₅₀.
- Ternary phase diagrams (GB-IL + Na₂SO₄ or K₃C₆H₅O₇) → ABS; EE_BSA% extraction.

**Key design choice**: derive the IL anion from an inert, non-metal-binding Good's buffer so a single compound provides both the solvent/extractant and pH control for fragile proteins.

## Results
| Property | Finding |
|----------|---------|
| Self-buffering | Mid-point pH/ranges ≈ parent buffers; buffer capacity usually higher; universal buffer linear pH 5.2–10.4 |
| BSA thermal stability | T_d ≈ 56 °C (Tricine); GB-ILs match conventional ILs but need no added buffer; [N4444]Br aggregates BSA (T_d 48→40 °C) |
| BSA secondary structure | Free BSA α-helix 57.6%; GB-ILs give **higher** helicity than bromide ILs, rising with concentration; order [N4444][Tricine] > [Emim][Tricine] > [N2222][Tricine] > [N1111][Tricine] |
| Ion binding (docking) | ΔG_bind: [N1111] −2.5, [N2222] −4.0, [N4444] −4.9, [Emim] −4.1 kcal mol⁻¹; affinity ↑ with alkyl chain; Tricine anion/zwitterion ~ −4.5/−4.6 kcal mol⁻¹ |
| Toxicity (EC₅₀, higher = safer) | Mostly non-toxic (EC₅₀ 179.77 mg dm⁻³ [N4444][CHES] → 44 302.87 mg dm⁻³ [N2222][MES]); ammonium < imidazolium toxicity; longer chain more toxic; anion [MES]<[TES]<[HEPES]<[Tricine]<[CHES] |
| ABS + extraction | [N4444][GB] + Na₂SO₄/citrate form ABS; **100% single-step BSA extraction**; CHES/MES anions salt out more easily; Na₂SO₄ stronger salting-out than citrate |

## Related Papers
- [[computational/taha-2015-novel-biocompatible-and-self-buffering-ionic]] — direct successor: swaps imidazolium/ammonium cations for biocompatible **cholinium** and uses biodegradable **PPG 400** (polymer–IL ABS) to extract IgY
- [[computational/pedro-2018-cholinium-based-goods-buffers]] — extends cholinium GB-ILs from protein extraction to **RNA stabilization** (+14 °C Tm, 30-day RT stability)
- [[computational/verissimo-2026-ionic-liquids-deep-eutectic]] — review situating GB-ILs among biocompatible IL/DES platforms for nucleic-acid biopharmaceuticals
- [[computational/yu-2026-ionic-liquids-as-alternative]] — choline–amino-acid ILs applied to LNP-mediated mRNA delivery
