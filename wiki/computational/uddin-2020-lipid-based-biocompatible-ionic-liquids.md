---
title: "Lipid based biocompatible ionic liquids: synthesis, characterization and biocompatibility evaluation"
authors: Shihab Uddin, Md. Raihan Chowdhury, Rie Wakabayashi, Noriho Kamiya, Muhammad Moniruzzaman, Masahiro Goto
year: 2020
doi: 10.1039/D0CC04491A
source: uddin-2020-lipid-based-biocompatible-ionic-liquids.md
category: computational
pdf_path: C:/Users/User/Desktop/llm-wiki/papers/Lipid based biocompatible ionic liquids.pdf
pdf_filename: Lipid based biocompatible ionic liquids.pdf
source_collection: external
tags: [ionic-liquid, lipid-based-ionic-liquid, LBIL, synthesis, EDMPC, fatty-acid-anion, biocompatibility, transdermal, characterization]
---

## Summary
This Communication reports the **first lipid-based biocompatible ionic liquids (LBILs)** — ILs where *both ions are lipids*: a cationic ethylated phosphocholine (**EDMPC**, from DMPC) paired one-to-one with a long-chain fatty-acid anion (**stearate C18:0, oleate C18:1, or linoleate C18:2**). It is the **founding synthesis paper** of the Goto-group LBIL platform, and the direct source of the synthesis route later reused for antisense (Toyofuku 2023) and mRNA delivery ([[computational/tanaka-2026-lipid-based-ionic-liquids-enable]]). The LBILs are fully characterized (NMR, FTIR, MALDI-TOF MS, DSC, DLS, UV, COSMO-RS) and shown to be **highly biocompatible** on a 3-D human epidermis model, motivating their use in IL-mediated transdermal drug delivery.

If you want the **detailed LBIL synthesis** (reagent ratios, conditions, purification, anion exchange), this is the most complete account in the wiki — more so than Tanaka 2026, which references but does not re-state the quantitative procedure.

## Key Contributions
- **First LBILs with lipid moieties as both cation and anion** (prior bio-ILs used amino acids, sugars, or short carboxylates).
- Three LBILs varying **only in anion unsaturation** — [EDMPC][Ste], [EDMPC][Ole], [EDMPC][Lin] — isolating the effect of C=C double bonds on physical state and thermal behavior.
- Complete **synthesis + physicochemical/thermal characterization** and a standardized **skin-irritation biocompatibility** demonstration.
- Establishes EDMPC + linoleate as a low-toxicity lipid IL, the building block carried into later RNA-delivery work.

## Methodology and Architecture

**Three-step synthesis** (Fig. 1; details in SI §1.2–1.3):

1. **O-ethylation → cationic lipid.** DMPC + ethyl trifluoromethanesulfonate (EtFMS) at **1:1 mol ratio**, CHCl₃, **45 °C, 12 h, N₂** → **EDMPC-SO₃CF₃** (triflate salt). [Macdonald 1999 method.]
2. **Chloride exchange (phase separation).** Dissolve in chloroform, add **0.2 N HCl** with shaking → **EDMPC-Cl**; triflate byproduct + excess HCl discarded with the aqueous phase; Milli-Q wash; **freeze-dry**. ([EDMPC]⁺ MALDI-TOF m/z 706.252; calc. 706.856.)
3. **Anion exchange → LBIL.** EDMPC-Cl + fatty acid (Ste/Ole/Lin) at **equimolar ratio**, chloroform, **45 °C, ~12 h overnight, N₂, light-protected**; **freeze-dry**. Volatile HCl byproduct evaporates; **no residual Cl⁻** (silver nitrate test).

**Characterization**: TLC (Rf), ¹H-NMR (400 MHz, CDCl₃), FTIR (400–4000 cm⁻¹), MALDI-TOF MS, DSC, elemental analysis, Karl-Fischer (moisture), DLS + UV-vis (solubility/micelles), CLSM, COSMO-RS modeling.

**Biocompatibility**: skin-irritation MTT assay on **LabCyte™ EPI-MODEL 24** reconstructed human epidermis; LBILs in IPM at 5–100% w/w; vs emim-TFSA, bmim-Tf₂N, SDS controls.

## Results

| LBIL | Anion (C18) | State (RT) | Tm / Tcr (DSC) | Notes |
|------|-------------|-----------|----------------|-------|
| **[EDMPC][Lin]** | linoleate C18:2 | viscous liquid | **20.8 / 15.4 °C** | weakest H-bonding (COSMO-RS); lowest Tm |
| [EDMPC][Ole] | oleate C18:1 | highly viscous liquid | 24.3 / 19.2 °C | intermediate |
| [EDMPC][Ste] | stearate C18:0 | semi-solid | 54.9 / 7.3 °C | strongest H-bonding; highest Tm |

- **Tm tracks degree of unsaturation** (more C=C → lower Tm, more fluid); same carbon count, different double bonds.
- **Ion pairing confirmed**: no free –COOH peak in NMR (δ 11.68–11.97) or FTIR (2500–3300 cm⁻¹) → carboxylate↔ammonium interaction.
- **pH** 5.8–6.1 (20 mg/mL in water) → topical/TDDS-compatible.
- **Solubility**: freely soluble in polar + nonpolar organics; **sparingly soluble in water**, forming **~150–200 nm micelles** (DLS/CLSM); molecular-level in hexane.
- **Biocompatibility**: ≥97% viability at 20% w/v for all three; tolerated up to 50% w/v; vastly better than emim-TFSA (69%), bmim-Tf₂N (27%), SDS (1.9%). Neat (100%) [EDMPC][Lin] ~52%.
- **In vitro / materials characterization only** — no drug or nucleic-acid delivery in this paper.

## Related Papers
- [[computational/tanaka-2026-lipid-based-ionic-liquids-enable]] — same group; reuses this EDMPC + linoleate chemistry but **varies the cation tail (C14/C16/C18)** for **mRNA delivery**. This 2020 paper is its synthesis foundation (and gives the quantitative procedure Tanaka omits).
- [[computational/egorova-2021-ionic-liquids-prospects-for-nucleic]] — review situating cationic/lipid ILs (head + lipophilic tail, chain-length SAR) in nucleic-acid handling and delivery.
- [[computational/mirhadi-2024-utilizing-ionic-liquids-as-eco]] — review of ILs as biocompatible nucleic-acid delivery carriers and nano-vector components.
- [[computational/verissimo-2026-ionic-liquids-deep-eutectic]] — perspective framing surface-active / API-ILs as combined protection + delivery agents; LBILs are an instance.
- [[cell-biology/mitragotri-2024-choline-geranate-cage-multifaceted]] / [[cell-biology/zakrewsky-2014-ionic-liquids-as-a-class]] — CAGE IL for transdermal small-molecule/siRNA delivery; parallel lipid-IL-for-skin lineage with different chemistry.
