---
title: "Lipid based biocompatible ionic liquids: synthesis, characterization and biocompatibility evaluation"
authors: Shihab Uddin, Md. Raihan Chowdhury, Rie Wakabayashi, Noriho Kamiya, Muhammad Moniruzzaman, Masahiro Goto
year: 2020
doi: 10.1039/D0CC04491A
category: computational
pdf_path: C:/Users/User/Desktop/llm-wiki/papers/Lipid based biocompatible ionic liquids.pdf
pdf_filename: Lipid based biocompatible ionic liquids.pdf
source_collection: external
---

## One-line Summary
The **first** lipid-based biocompatible ionic liquids (LBILs): the cationic phospholipid EDMPC (ethylated DMPC) paired one-to-one with a long-chain fatty-acid anion (stearate C18:0, oleate C18:1, or linoleate C18:2), made by O-ethylation → chloride exchange → fatty-acid neutralization; fully characterized (NMR/FTIR/MS/DSC/DLS) and shown to be highly biocompatible on a 3-D human epidermis model — the founding synthesis behind the Goto-group LBIL platform later used for antisense (Toyofuku 2023) and mRNA delivery ([[computational/tanaka-2026-lipid-based-ionic-liquids-enable]]).

## 1. Document Information
- **Journal**: Chemical Communications (ChemComm), Royal Society of Chemistry, 2020; Accepted Manuscript, published online 07 Oct 2020
- **DOI**: 10.1039/D0CC04491A
- **Type**: Communication
- **Affiliations**: Department of Applied Chemistry / Advanced Transdermal DDS Center / Center for Future Chemistry, Kyushu University (Fukuoka, Japan); Chemical Engineering Dept., Universiti Teknologi PETRONAS (Malaysia). Corresponding author: Masahiro Goto.
- **Funding**: MEXT KAKENHI JP20K20440; S. Uddin on a MEXT scholarship.

## 2. Key Contributions
- **First-ever LBILs** in which long-chain lipid moieties form **both** the cation (EDMPC phosphocholine) and the anion (C18 fatty acid) — distinct from prior bio-ILs built from amino acids / carbohydrates / short carboxylates.
- Three LBILs differing **only in anion unsaturation**: **[EDMPC][Ste]** (C18:0), **[EDMPC][Ole]** (C18:1), **[EDMPC][Lin]** (C18:2).
- Establishes the **synthesis + full physicochemical/thermal characterization** and demonstrates **excellent skin biocompatibility**, proposing LBILs for IL-mediated transdermal drug delivery (TDDS).
- Shows **degree of unsaturation tunes melting point / phase behavior** (more double bonds → lower Tm, more fluid).

## 3. Methodology and Architecture

### LBIL synthesis (detailed, from main text + SI §1.2–1.3)
**Materials**: DMPC and ethyl trifluoromethanesulfonate (EtFMS) from TCI; stearic/oleic/linoleic acids from Sigma-Aldrich; dehydrated CHCl₃, chloroform-d from Fujifilm Wako.

**Step 1 — Cationic lipid (O-ethylation):**
- DMPC + EtFMS at **1:1 mol ratio**, in **CHCl₃**, **45 °C, 12 h, continuous N₂ flow** → **EDMPC-SO₃CF₃** (ethylated phosphocholine triflate salt). (Method per Macdonald 1999, SI ref 1.)
- Confirmed by TLC (CHCl₃:MeOH 9:1 v/v; p-anisaldehyde stain), ¹H-NMR (JEOL ECZ400S, 400 MHz, CDCl₃), FTIR, MS.

**Step 2 — Chloride form (phase separation, Fig. S2):**
- Dissolve EDMPC-SO₃CF₃ in chloroform; add **0.2 N HCl** with shaking → **EDMPC-Cl** in the nonaqueous phase; triflate byproduct + unreacted HCl partition into and are discarded with the aqueous phase.
- Further wash with Milli-Q water; remove chloroform + water by **freeze-drying**.
- Purity/identity by TLC (Rf ≈ 0.70 in 10% MeOH/CHCl₃), ¹H-NMR, FTIR, MALDI-TOF MS (**[EDMPC]⁺ m/z 706.252**, calc. 706.856), and elemental analysis.

**Step 3 — Anion exchange to LBIL:**
- EDMPC-Cl + fatty acid (stearic / oleic / linoleic) at **equimolar ratio**, in **chloroform**, **45 °C, overnight (~12 h), continuous N₂, light-protected**.
- Freeze-dry the reaction solution → LBIL. The **HCl byproduct is volatile and evaporates**; complete removal of Cl⁻ confirmed by **silver nitrate test**.
- Products: **[EDMPC][Lin]**, **[EDMPC][Ole]**, **[EDMPC][Ste]**.

Overall scheme (Fig. 1): (i) EtFMS, CHCl₃, 45 °C, 12 h → (ii) 0.2 N HCl → (iii) fatty acid, CHCl₃, 45 °C, 12 h.

### Characterization toolbox (SI §1.4)
- **TLC** (10% MeOH/CHCl₃, PMA stain, Rf); **¹H-NMR** (400 MHz, CDCl₃, Delta-V software); **FTIR** (PerkinElmer, 400–4000 cm⁻¹, 20 scans, diamond ATR); **MALDI-TOF MS** (Bruker Autoflex II, 3-HPA matrix); **Karl-Fischer** water content (20% w/w in hexane); **DSC** (Hitachi TG/DTA 7300, N₂ 30 mL/min); **DLS + UV-vis** (Malvern Zetasizer / JASCO V-750) for solubility; **CLSM** for micelles; **COSMO-RS** (ADF 2019-301) structure/H-bond modeling; **elemental analysis**.

### Biocompatibility assay (SI §1.8)
- **Skin irritation test** on artificial 3-D human epidermis **LabCyte™ EPI-MODEL 24**, MTT readout (650/570 nm), % viability vs untreated control.
- LBILs in IPM at 5/10/20/50/100% (w/w); comparators emim-TFSA, bmim-Tf₂N (moderately toxic ILs), SDS (positive), IPM/PBS (negative). Two-way ANOVA + Dunnett's test.

## 4. Key Results and Benchmarks
- **Physical state (RT)**: [EDMPC][Lin] viscous liquid; [EDMPC][Ole] highly viscous liquid; [EDMPC][Ste] semi-solid.
- **NMR evidence of ion pairing**: no free-carboxylic-acid peak (δ 11.68–11.97); unsaturated –CH=CH– at δ ~5.34 (4H for Lin, 2H for Ole, none for Ste). **FTIR**: no free –COOH band (2500–3300 cm⁻¹) → carboxylate↔ammonium interaction.
- **Thermal (DSC, Table 1)** — Tm / Tcr: **[EDMPC][Lin] 20.8 / 15.4 °C**, **[EDMPC][Ole] 24.3 / 19.2 °C**, **[EDMPC][Ste] 54.9 / 7.3 °C**. Tm tracks **degree of unsaturation** (more double bonds → lower Tm); COSMO-RS: weakest H-bonding for Lin, strongest for Ste.
- **pH** (20 mg/mL in water): **5.8–6.1** → suitable for topical/TDDS.
- **Solubility**: freely/very soluble in polar (IPM, IPA, EtOH, MeOH, DMSO) and nonpolar (hexane, heptane, octane, dodecane, toluene) solvents; **sparingly soluble in water** — forms **micelles ~150–200 nm** (DLS/CLSM); molecular-level dissolution in hexane (UV at 237 nm, R²=0.9995). Micelle size + count rate rise with concentration (1→20 mg/mL: 135→485 nm).
- **Biocompatibility**: up to **50% w/v** LBIL in IPM does not significantly reduce viability; at 20% w/v all three ≈ PBS/IPM (97–101%). Far superior to **emim-TFSA (69%), bmim-Tf₂N (27%), SDS (1.9%)**. At 100% neat, [EDMPC][Lin] ~52%, [EDMPC][Ole] ~50%.
- **Elemental analysis / RI / Karl-Fischer** all consistent (Tables S1, S6); moisture 3.1–3.9%.

## 5. Limitations and Future Work
- **No drug/nucleic-acid delivery demonstrated here** — this paper establishes the materials and their biocompatibility only; therapeutic cargo (antisense, mRNA) comes in later Goto-group work.
- Single cation (EDMPC, C14 myristoyl tails); only three C18 anions; cation-tail variation not explored (later done in [[computational/tanaka-2026-lipid-based-ionic-liquids-enable]]).
- Biocompatibility limited to a skin-irritation (epidermis) model; no systemic toxicity, no in vivo permeation/efficacy.

## 6. Related Work
- **[[computational/tanaka-2026-lipid-based-ionic-liquids-enable]]** — same Goto group; reuses this exact EDMPC + linoleate chemistry but **varies the cation tail** (DMPC/DPPC/DSPC, C14/C16/C18) and applies it to **mRNA delivery**. This 2020 paper is the synthesis foundation.
- **Toyofuku et al. 2023** (ACS Appl. Mater. Interfaces 15, 33299) — intermediate step: fixes EDMPC, **varies the anion** ([EDMPC][Lin/Ole/Ste]) for **antisense oligonucleotide** transdermal delivery; reports the anion-dependent cytotoxicity that selects linoleate. (Not yet in wiki.)
- **Macdonald et al. 1999** (J. Pharm. Sci. 88, 896) — source of the DMPC O-ethylation (cationic-lipid) method (SI ref 1).
- **Dharamdasani/Mitragotri 2020** (J. Control. Release 323, 475) — siRNA transdermal delivery with hydrophobic cations + CAGE IL → motivates lipid-IL skin delivery (→ [[cell-biology/mitragotri-2024-choline-geranate-cage-multifaceted]], [[cell-biology/zakrewsky-2014-ionic-liquids-as-a-class]]).
- **[[computational/egorova-2021-ionic-liquids-prospects-for-nucleic]]** / **[[computational/mirhadi-2024-utilizing-ionic-liquids-as-eco]]** — reviews placing lipid/cationic ILs in the nucleic-acid delivery landscape.

## 7. Glossary
- **LBIL (Lipid-Based Ionic Liquid)**: ionic liquid whose ions are themselves lipids — here a cationic phosphocholine + a fatty-acid anion.
- **EDMPC**: 1,2-dimyristoyl-sn-glycero-3-**ethyl**-phosphatidylcholine; the permanently cationic (quaternized) lipid obtained by O-ethylating the phosphate of DMPC.
- **DMPC**: 1,2-dimyristoyl-sn-glycero-3-phosphocholine (C14 myristoyl tails), the neutral starting phospholipid.
- **EtFMS / ethyl triflate**: ethyl trifluoromethanesulfonate; the O-alkylating (ethylating) agent.
- **[EDMPC][Ste] / [Ole] / [Lin]**: LBILs with stearate (C18:0) / oleate (C18:1) / linoleate (C18:2) anions.
- **EDMPC-SO₃CF₃ / EDMPC-Cl**: the triflate and chloride intermediate salts of the cation before anion exchange.
- **LabCyte EPI-MODEL**: reconstructed 3-D human epidermis used in the standardized in-vitro skin-irritation (MTT) test.
- **COSMO-RS**: quantum-chemistry-based thermodynamic model used to predict H-bonding / structure of the LBILs.
