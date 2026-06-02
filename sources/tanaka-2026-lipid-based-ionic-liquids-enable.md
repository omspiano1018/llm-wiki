---
title: "Lipid-based ionic liquids enable efficient messenger RNA intracellular delivery"
authors: Keisuke Tanaka, Yoshirou Kawaguchi, Rie Wakabayashi, Noriho Kamiya, Masahiro Goto
year: 2026
doi: 10.1093/chemle/upag025
category: computational
pdf_path: C:/Users/painteroh/Desktop/llm-wiki/papers/tanaka-2026-lipid-based-ionic-liquids-enable.pdf
pdf_filename: tanaka-2026-lipid-based-ionic-liquids-enable.pdf
source_collection: external
---

## One-line Summary
Cationic phospholipids (DMPC, DPPC, DSPC) are ethylated and paired with a linoleate anion to make lipid-based ionic liquids (LBILs) that complex mRNA; the shortest-tail variant [EDMPC][Lin] (myristoyl) forms the most stable, positively charged complexes and gives the highest NanoLuc-mRNA transfection in HeLa cells — establishing LBILs as a tunable, single-molecule platform for intracellular mRNA delivery.

## 1. Document Information
- **Journal**: Chemistry Letters, 2026, **55**, upag025 (Oxford University Press, on behalf of the Chemical Society of Japan)
- **DOI**: 10.1093/chemle/upag025; advance access 9 Feb 2026
- **Type**: Letter (short communication)
- **Timeline**: Received 2025-12-07; revised 2026-01-24; accepted 2026-01-27; typeset 2026-02-26
- **Affiliations**: Department of Applied Chemistry & Center for Future Chemistry, Kyushu University (Fukuoka, Japan); Goto group (Advanced Transdermal DDS Center)
- **Funding**: JSPS KAKENHI (JP23KJ1731, JP24H00397); AMED (21ak0101174h0001)

## 2. Key Contributions
- **First demonstration that LBILs deliver mRNA** (large, highly anionic) — extending prior LBIL work that delivered only antisense oligonucleotides (Toyofuku et al. 2023, same group).
- **Systematic study of cation (lipid tail) design**, the variable previously left fixed: three cationic phospholipids of increasing alkyl chain length (C14 myristoyl, C16 palmitoyl, C18 stearoyl) paired with a single linoleate anion.
- Shows that **hydrophobic tail length dictates complex size, surface charge, mRNA binding, and transfection** — not monotonically, so packing/headgroup/hydration effects matter.
- Identifies **[EDMPC][Lin] (myristoyl)** as the best performer: smallest, most positive, most stable complex and highest gene expression.

## 3. Methodology and Architecture

### LBIL synthesis (two-step, per ref. 17)
1. **Ethylation**: phospholipid (DMPC / DPPC / DSPC) + ethyl trifluoromethanesulfonate (1:1 mol), 45 °C, 12 h under N₂ → ethylated phospholipid triflate.
2. Dissolve in chloroform; add 0.2 N HCl with shaking → **chloride form**; centrifuge, discard HCl phase (removes triflate byproduct), water-wash; lyophilize.
3. **Anion exchange**: ethylated phospholipid chloride + sodium linoleate (equimolar) in chloroform, 45 °C, ~12 h under N₂, light-protected; freeze-dry → IL-type lipid.
4. Validated by ¹H NMR (Supplementary Fig. S1); stored in ethanol at 10 mg/mL, −80 °C.
- Products: **[EDMPC][Lin]**, **[EDPPC][Lin]**, **[EDSPC][Lin]** (E = ethylated; cation from DMPC/DPPC/DSPC; Lin = linoleate).

### Complexation & characterization
- **LBIL + mRNA** mixed at **N/P (amine:phosphate) = 10:1**, 1:19 volume ratio (LBIL-in-ethanol : mRNA-in-water), RT 5 min, 100 µL final.
- **DLS** (Malvern Zetasizer Ultra) for size; **zeta potential** (10× dilution, n = 5); **agarose gel electrophoresis** (1% gel, MOPS pH 7.0, 150 V, 20 min; 1.0 µg mRNA/lane) for binding/retardation.

### Transfection assay
- **HeLa cells**, 10,000/well in 96-well plates; serum/antibiotic-free MEM during dosing.
- **NanoLuc reporter mRNA**, 500 ng/well, 24 h incubation; Nano-Glo luminescence, normalized to untreated; n = 3, Tukey's test.
- **Lipofectamine** as commercial benchmark.

### Supplementary Information (this paper — `papers/tanaka-2026-lipid-based-ionic-liquids-enable-si.docx`)
The SI provides characterization and the mRNA preparation protocol; it does **not** add quantitative LBIL synthesis reagent amounts.
- **¹H-NMR of the three LBILs** ([EDMPC][Lin], [EDPPC][Lin], [EDSPC][Lin]) recorded in **DMSO-d₆, 400 MHz** (JEOL Delta-V v5.0.5.1) — Fig. S1; confirms IL structure.
- **Size distribution of LBILs alone** (no mRNA) in EtOH/water by DLS, same mixing protocol (Fig. S2): EDMPC–Lin and EDPPC–Lin form **submicron** populations, whereas **EDSPC–Lin forms larger aggregates** — consistent with the longer C18 tail's poor solubility.
- **NanoLuc mRNA made in-house by IVT** — Takara **IVTpro™ T7 mRNA Synthesis Kit**: 20 µL reaction (2 µL 10× Enzyme Mix; 2 µL each ATP/CTP/UTP; 1.5 µL modified-NTP mix; 1 µg linearized DNA template; 1 µL RNase inhibitor; NF water), 37 °C 2 h → +4 µL DNase I, 37 °C 15 min → **LiCl precipitation** (−20 °C ≥30 min, 20,000 g 15 min 4 °C), 70% EtOH wash, dissolve in 100 µL NF water, NanoDrop quant, store −20 °C. Uses **modified NTPs** (chemically modified mRNA).
- **Full NanoLuc mRNA sequence** is listed (capped/UTR + ORF + ~3′ poly(A) tail).
> Note the NMR solvent here is **DMSO-d₆** (cf. the predecessor antisense study, which used CDCl₃).

## 4. Key Results and Benchmarks
- **Particle size**: single peak for EDMPC-Lin; multiple/heterogeneous peaks for EDPPC-Lin and EDSPC-Lin. Size order **EDMPC-Lin < EDPPC-Lin < EDSPC-Lin** (longer tails → poorer water/ethanol solubility → aggregation).
- **Zeta potential**: EDMPC-Lin **+36.6 mV**, EDSPC-Lin **+23.2 mV** (cationic heads exposed); EDPPC-Lin anomalously **−36.6 mV** (even more negative than free mRNA), implying incomplete complexation.
- **Gel electrophoresis**: EDMPC-Lin and EDSPC-Lin retain mRNA in the well (charge neutralized); EDPPC-Lin shows a migrating band ≈ native mRNA → portion of mRNA remains free/uncomplexed.
- **Transfection**: EDMPC-Lin and EDSPC-Lin significantly higher than mRNA alone; **EDPPC-Lin ≈ free mRNA** (no benefit). **EDMPC-Lin (myristoyl) highest** of all LBILs.
- Trend is **non-monotonic** in tail length → lipid packing, headgroup presentation, hydration also govern complex formation; more positive surface charge correlated with better delivery here.

## 5. Limitations and Future Work
- **In vitro only** (HeLa, single reporter); no in vivo, no cytotoxicity/biocompatibility data reported in the letter.
- Only **three cationic lipids and a single anion (linoleate)**; broader anion/cation space and N/P optimization not explored.
- Mechanism of the EDPPC-Lin anomaly (negative zeta, poor binding) not resolved.
- Stability/storage of complexes, endosomal-escape mechanism, and quantitative comparison vs. Lipofectamine magnitude not detailed in the main text.

## 6. Related Work
- **Toyofuku et al. 2023** "Non-Invasive Transdermal Delivery of Antisense Oligonucleotides with Biocompatible Ionic Liquids" (ACS Appl. Mater. Interfaces, 15, 33299; DOI 10.1021/acsami.3c03900) — same group; direct predecessor that **fixed the EDMPC cation and varied the anion** ([EDMPC][Lin/Ole/Ste]) for antisense delivery. Its SI reported anion-dependent HeLa cytotoxicity (EC₅₀: [EDMPC][Lin] 40.8 mM ≫ [EDMPC][Ste] 8.67 mM > [EDMPC][Ole] 3.03 mM), rationalizing **linoleate** as the low-toxicity anion carried into this mRNA study. Tanaka inverts the design axis — fixing linoleate and varying the **cation tail (C14/C16/C18)**.
- **Yu et al. 2026** — choline-based ILs replacing PEG in mRNA-LNPs; structurally distinct (IL as LNP stabilizer, not the cationic lipid itself) (→ [[computational/yu-2026-ionic-liquids-as-alternative]]).
- **Veríssimo et al. 2026** — review framing surface-active ILs / API-ILs as combined protection + delivery agents for nucleic acids (→ [[computational/verissimo-2026-ionic-liquids-deep-eutectic]]).
- **Mitragotri 2024 / Zakrewsky 2014** — CAGE (choline geranate) IL for transdermal small-molecule and siRNA delivery (→ [[cell-biology/mitragotri-2024-choline-geranate-cage-multifaceted]], [[cell-biology/zakrewsky-2014-ionic-liquids-as-a-class]]).
- Mrksich et al. 2024 (ref. 17, helper-lipid alkyl-chain tuning of LNP surface packing); López Espinar et al. 2025 (ref. 18, cationic lipid–nucleic acid complex behavior).

## 7. Glossary
- **LBIL (Lipid-Based Ionic Liquid)**: ionic liquid whose ions are lipids — here a cationic ethylated phosphocholine paired with a fatty-acid (linoleate) anion; the lipid itself is the IL, not an additive.
- **[EDMPC][Lin] / [EDPPC][Lin] / [EDSPC][Lin]**: LBILs from ethylated DMPC (C14), DPPC (C16), DSPC (C18) cations + linoleate anion.
- **DMPC / DPPC / DSPC**: 1,2-diacyl-sn-glycero-3-phosphocholines with myristoyl / palmitoyl / stearoyl (C14/C16/C18) tails.
- **Linoleate (Lin)**: anion of linoleic acid (C18:2 polyunsaturated fatty acid).
- **N/P ratio**: molar ratio of cationic amine groups (carrier) to phosphate groups (nucleic acid); here 10:1.
- **Zeta potential**: particle surface charge in suspension; positive values favor cell-membrane association and uptake.
- **NanoLuc**: small luciferase reporter; luminescence reports successful mRNA translation (transfection efficiency).
- **Ethyl triflate**: ethyl trifluoromethanesulfonate; alkylating agent that ethylates the phosphate to give a permanent cationic (quaternized) phospholipid.
