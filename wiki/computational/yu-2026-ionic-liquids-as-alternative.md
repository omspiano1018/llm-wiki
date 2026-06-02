---
title: "Ionic liquids as alternative stabilizers for lipid nanoparticles used to deliver mRNA"
authors: Haitao Yu, Natalia Martinez, Qi Han, Mohamad El Mohamad, Brendan Dyett, Steven Bozinovski, Leonie van 't Hag, Calum John Drummond, Jiali Zhai
year: 2026
doi: 10.1098/rsta.2024.0310
source: yu-2026-ionic-liquids-as-alternative.md
category: computational
pdf_path: C:/Users/painteroh/Desktop/llm-wiki/papers/yu-2026-ionic-liquids-as-alternative.pdf
pdf_filename: yu-2026-ionic-liquids-as-alternative.pdf
source_collection: external
tags: [ionic-liquid, LNP, mRNA-delivery, PEG-alternative, lipid-nanoparticle, endosomal-escape, SAXS, macrophage, choline]
---

## Summary
Yu et al. (2026) replace the PEGylated stabilizer (F127 polymer) in mRNA lipid nanoparticles (LNPs) with choline-based ionic liquids — choline hexanoate (Cho Hex), choline aspartate (Cho Asp), and choline glutamate (Cho Glu). IL-incorporated LNPs achieve **~85% mRNA transfection efficiency in alveolar macrophages**, compared to ~50% for F127-stabilized LNPs. SAXS experiments reveal that acidification at endosomal pH drives structural transitions to inverse lipid mesophases (cubic/hexagonal), facilitating endosomal escape. This work provides a mechanistic rationale for using choline ILs as PEG alternatives in next-generation genetic nanomedicines.

## Key Contributions
- **~85% transfection efficiency** in alveolar macrophages (MH-S cells) vs ~50% for PEGylated control
- Choline amino acid ILs (Asp, Glu) form more stable LNPs without PEG than choline hexanoate
- **pH-driven inverse mesophase transitions** (characterized by SAXS) linked mechanistically to improved endosomal escape and transfection
- Addresses key limitation of PEGylated LNPs: anti-PEG antibody induction after repeat dosing
- Establishes structure–performance relationships for IL-stabilized LNP design

## Methodology and Architecture
**LNP composition**: SM-102 (ionizable lipid) / monoolein (MO) / cholesterol = 50:30:20 molar ratio; IL at 10 wt% relative to lipid mass.

**Fabrication**: Microfluidic mixing (lipid in methanol + IL in citrate buffer pH 3); dialysis in Milli-Q water to remove solvent and free IL.

**Key measurements**:
- DLS: particle size and PDI
- ELS (electrophoretic light scattering): zeta potential
- SAXS: lipid mesophase structure at pH 3 and pH 7.4 (acidification mimics endosomal environment)
- Flow cytometry / fluorescence microscopy: transfection readout in MH-S macrophages

**Mechanism**: At acidic endosomal pH (~5), IL-LNPs transition from lamellar to inverse bicontinuous cubic or hexagonal mesophases. These non-lamellar structures destabilize the endosomal membrane, releasing mRNA into the cytoplasm. This is enabled by the combination of monoolein (a lipid known to form inverse phases) with choline ILs that modulate phase transition pH.

## Results
| Parameter | IL-LNPs (Asp/Glu) | F127-LNPs |
|-----------|------------------|-----------|
| Particle size | ~130–150 nm | ~77 nm |
| PDI | <0.1 | 0.12 |
| Zeta potential | ~+20 mV | +16 mV |
| Transfection (MH-S) | ~85% | ~50% |
| PEG content | None | Yes |

## Related Papers
- [[computational/pedro-2018-cholinium-based-goods-buffers]] — cholinium Good's buffer ILs for RNA stabilization; foundational work on IL–RNA compatibility
- [[computational/de-silva-2026-a-biocompatible-and-recyclable]] — choline glutamate (same anion as Cho Glu here) for plant RNA preservation; IL stability angle
