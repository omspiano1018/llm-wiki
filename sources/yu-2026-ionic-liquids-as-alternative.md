---
title: "Ionic liquids as alternative stabilizers for lipid nanoparticles used to deliver mRNA"
authors: Haitao Yu, Natalia Martinez, Qi Han, Mohamad El Mohamad, Brendan Dyett, Steven Bozinovski, Leonie van 't Hag, Calum John Drummond, Jiali Zhai
year: 2026
doi: 10.1098/rsta.2024.0310
category: computational
pdf_path: C:/Users/User/Desktop/llm-wiki/papers/yu-2026-ionic-liquids-as-alternative.pdf
pdf_filename: yu-2026-ionic-liquids-as-alternative.pdf
source_collection: external
---

## One-line Summary
Choline-based ionic liquids (hexanoate, aspartate, glutamate) replace PEGylated stabilizers in mRNA-LNPs, achieving ~85% transfection efficiency in alveolar macrophages via pH-induced inverse lipid mesophase transitions.

## 1. Document Information
- **Journal**: Philosophical Transactions of the Royal Society A 384: 20240310 (2026)
- **Institution**: RMIT University (Molecular Assembly Lab, Zhai/Drummond); Monash University
- **Received**: 2025-06-10; Accepted: 2025-11-20
- **Part of**: Discussion meeting issue "Ionic liquids and the future of soft materials"

## 2. Key Contributions
- Replaced PEG-lipid (F127 polymer) in LNPs with choline-based ILs for mRNA delivery
- **~85% mRNA transfection efficiency** in murine alveolar macrophages (MH-S cells) vs ~50% for F127-stabilized LNPs
- IL-incorporated LNPs form **inverse lipid mesophases** under acidic pH (endosomal pH), enabling endosomal escape
- SAXS (small-angle X-ray scattering) used to characterize pH-dependent lipid phase transitions
- Established structure–function relationship linking lipid mesophase evolution to transfection efficiency

## 3. Methodology and Architecture

### LNP formulation
- **Lipid composition**: SM-102 / monoolein (MO) / cholesterol at 50:30:20 molar ratio
- **Stabilizer**: one of three choline-based ILs at 10 wt% relative to total lipid, replacing F127 polymer
  - **Cho Hex** (choline hexanoate)
  - **Cho Asp** (choline aspartate)
  - **Cho Glu** (choline glutamate)
- **Formulation method**: microfluidic mixing of lipid methanolic solution with IL-containing citrate buffer (10 mM, pH 3); dialysis to remove solvent and free ILs

### Physicochemical characterization
| Measurement | Method | Result |
|-------------|--------|--------|
| Particle size (Zave) | DLS | Hex 149±1 nm, Asp 130±5 nm, Glu 148±6 nm |
| PDI | DLS | <0.1 for all IL-LNPs |
| Zeta potential | ELS | ~+20 mV (all IL-LNPs) vs +16±7 mV (F127) |
| Lipid phase | SAXS | Inverse mesophase at acidic pH |

### Biological characterization
- **Cell line**: murine alveolar macrophage MH-S cells
- **mRNA**: reporter mRNA (fluorescence readout)
- **Transfection readout**: flow cytometry / fluorescence microscopy
- **Stability**: colloidal stability over time at physiological and storage conditions

### Mechanism: endosomal escape
At endosomal pH (~5), IL-incorporated LNPs transition to **inverse lipid mesophases** (cubic/hexagonal phases characterized by SAXS). These highly curved phases disrupt the endosomal membrane, releasing mRNA cargo into the cytoplasm.

## 4. Key Results and Benchmarks
- **Transfection efficiency**: ~85% for all three IL-LNPs vs ~50% for F127-stabilized control
- **Particle size**: ~130–150 nm (IL-LNPs) vs 77 nm (F127-LNPs); all monodisperse (PDI <0.1)
- **Surface charge**: +20 mV (IL-LNPs); quaternary ammonium of choline localizes at lipid–water interface
- **pH-dependent structure**: SAXS confirms acidification-induced transition to ordered inverse lipid mesophases
- **Choline amino acid ILs** (Asp, Glu) form more stable LNP formulations than choline hexanoate in the absence of PEG
- Low toxicity of Cho Asp and Cho Glu confirmed in prior screening of 13 ILs across 4 cell lines

## 5. Limitations and Future Work
- In vitro only; no animal model (in vivo biodistribution not tested)
- Long-term storage stability of IL-LNPs not characterized
- Limited to macrophage cell line; lung epithelial or other targets not tested
- Immunogenicity advantage over PEG not directly confirmed in this study
- IL incorporation efficiency and leaching not quantified

## 6. Related Work
- Khare et al.: choline trans-2-hexenoate-coated LNPs for siRNA delivery to brain endothelial cells
- Pedro et al. 2018: choline GB-ILs for RNA stabilization (not delivery) (→ [[computational/pedro-2018-cholinium-based-goods-buffers]])
- De Silva et al. 2026: choline glutamate for plant RNA preservation (→ [[computational/de-silva-2026-a-biocompatible-and-recyclable]])
- COVID-19 mRNA vaccines (Pfizer BNT162b2, Moderna mRNA-1273): used PEGylated LNPs; anti-PEG IgG issues motivate PEG replacement
- Onpattro® (patisiran): first approved RNA interference LNP drug; also uses PEG-lipid

## 7. Glossary
- **LNP (Lipid Nanoparticle)**: nanoparticle composed of ionizable lipid, helper lipid, cholesterol, and stabilizer; gold-standard mRNA delivery vehicle
- **SM-102**: ionizable amino lipid (heptadecan-9-yl 8-((2-hydroxyethyl)(8-(nonyloxy)-8-oxooctyl)amino)octanoate); used in Moderna COVID-19 vaccine
- **Monoolein (MO)**: unsaturated monoglyceride that forms lyotropic liquid crystalline phases; key for endosomal escape
- **PEG (polyethylene glycol)**: hydrophilic polymer used as LNP stabilizer; causes immunogenicity upon repeat dosing
- **F127**: Pluronic F127; PEO-PPO block copolymer; PEGylated control in this study
- **SAXS**: small-angle X-ray scattering; used to determine nanoscale lipid mesophase structures
- **Inverse mesophase**: non-lamellar lipid phases (cubic, hexagonal) with water channels inside lipid matrix; high membrane-disruptive potential
- **Endosomal escape**: process by which nanoparticle cargo escapes the acidic endosome into cytoplasm; rate-limiting step in intracellular nucleic acid delivery
- **Alveolar macrophages**: lung-resident innate immune cells; relevant target for pulmonary gene therapy
- **PDI (Polydispersity Index)**: measure of size distribution; <0.1 indicates narrow, uniform distribution
